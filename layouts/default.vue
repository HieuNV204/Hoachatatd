<template>
  <v-app clipped-left>
    <v-app-bar fixed app height="80" color="white">
      <v-avatar rounded size="80px" class="mr-10">
        <img
          alt="Avatar"
          src="https://hoachatdaiviet.com/wp-content/uploads/2018/09/logo-daiviet.png"
        />
      </v-avatar>
      <v-tabs v-model="tab" align-tabs="center" grow>
        <v-tab>Trang chủ</v-tab>
        <v-tab>Giới thiệu</v-tab>
        <v-tab>Danh mục sản phẩm</v-tab>
        <v-tab>
          <v-menu bottom right>
            <template v-slot:activator="{ on, attrs }">
              <span v-bind="attrs" v-on="on">Hỗ trợ</span>
            </template>
            <v-sheet class="pa-2">
              <v-list dense>
                <v-list-item dense link href="/support" class="px-2">
                  <v-list-item-content>
                    <v-list-item-title class="text-body-2">
                      Mua hàng và thanh toán
                    </v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
                <v-divider></v-divider>
                <v-list-item dense link href="/support-transport" class="px-2">
                  <v-list-item-content>
                    <v-list-item-title class="text-body-2">
                      Chính sách giao hàng
                    </v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
                <v-divider></v-divider>
                <v-list-item dense link href="/support-change" class="px-2">
                  <v-list-item-content>
                    <v-list-item-title class="text-body-2">
                      Quy định đổi trả sản phẩm
                    </v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
                <v-divider></v-divider>
                <v-list-item dense link href="/support-security" class="px-2">
                  <v-list-item-content>
                    <v-list-item-title class="text-body-2">
                      Chính sách bảo mật
                    </v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
              </v-list>
            </v-sheet>
          </v-menu>
        </v-tab>
        <v-tab>Liên hệ</v-tab>
      </v-tabs>
    </v-app-bar>
    <v-main style="margin-bottom: 86px">
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
    <v-divider></v-divider>
    <v-footer>
      <v-row>
        <v-container
          class="d-flex justify-center justify-space-between"
          style="max-width: 1368px"
        >
          <div class="col pb-0 widget widget_text">
            <span class="widget-title">CÔNG TY TNHH AN THÀNH DANH</span>
            <div class="is-divider small"></div>
            <div class="textwidget">
              <p>
                <img
                  decoding="async"
                  loading="lazy"
                  class="wp-image-1120 aligncenter"
                  src="https://hoachatdaiviet.com/wp-content/uploads/2018/09/logo-daiviet1-700x400.png"
                  alt=""
                  width="184"
                  height="105"
                />
              </p>
              <p>
                <strong>&nbsp;</strong>là công ty chuyên nhập khẩu và&nbsp;sản
                xuất&nbsp;các loại&nbsp;phụ gia thực phẩm,&nbsp;màu thực
                phẩm,&nbsp;hương liệu,&nbsp;chất bảo quản,&nbsp;chất điều
                vị&nbsp;với&nbsp;hệ thống phân phối lớn nhất Toàn quốc.
              </p>
            </div>
          </div>
          <div id="text-3" class="col pb-0 widget widget_text">
            <span class="widget-title">Liên Hệ An Thành Danh</span>
            <div class="is-divider small"></div>
            <div class="textwidget">
              <v-icon class="mb-2 mr-2" color="blue">mdi-phone-classic</v-icon>
              <span>Call:</span>
              <span style="color: #1976d2">0876819988</span>
              <br />
              <v-icon class="mb-2 mr-2" color="blue">mdi-email</v-icon>
              <span>Email:</span>
              <span>
                <a href="mailto:lienhe@hoachatdaiviet.com">
                  lienhe@hoachatdaiviet.com
                </a>
              </span>
              <br />
              <v-icon class="mb-2 mr-2" color="blue">mdi-email</v-icon>
              <span>Địa chỉ đăng ký kinh doanh:</span>
              <span style="color: #1976d2">
                Xóm 3, thôn Văn Trai, xã Văn Phú, huyện Thường Tín, Thành phố Hà
                Nội
              </span>
            </div>
          </div>
          <div id="text-6" class="col pb-0 widget widget_text">
            <span class="widget-title">Hỗ Trợ Khách Hàng</span>
            <div class="is-divider small"></div>
            <div class="textwidget">
              <p>
                <a
                  title="Thanh toán và mua hàng"
                  href="/support"
                  target="_blank"
                  rel="noopener"
                  >Thanh toán và mua hàng</a
                >
              </p>
              <p>
                <a href="/support-change" target="_blank" rel="noopener"
                  >Chính sách giao hàng</a
                >
              </p>
              <p>
                <a href="/support-change">Chinh sách đổi trả sản phẩm</a>
              </p>
              <p>
                <a href="/support-security">Chính sách bảo mật thông tin</a>
              </p>
            </div>
          </div>
        </v-container>
      </v-row>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: "DefaultLayout",
  data() {
    return {
      tab: 0,
    };
  },
  computed: {
    path() {
      return window.location.pathname;
    },
  },
  watch: {
    tab(value) {
      switch (value) {
        case 0:
          this.$router.push("/");
          break;
        case 1:
          this.$router.push("/info");
          break;
        case 2:
          this.$router.push("/category");
          break;
        case 3:
          if (!this.path.includes("support")) this.$router.push("/support");
          break;
        case 4:
          this.$router.push("/contact");
          break;

        default:
          break;
      }
    },
  },
  mounted() {
    if(this.path.includes('/info'))         this.tab = 1;
    if(this.path.includes('/category'))         this.tab = 2;
    if(this.path.includes('/support'))         this.tab = 3;
    if(this.path.includes('/contact'))         this.tab = 4;
  },
};
</script>
<style scoped>
h3.widget-title,
span.widget-title {
  text-transform: none;
}

span.widget-title {
  font-size: 1em;
  font-weight: 600;
}
.uppercase,
h6,
th,
span.widget-title {
  line-height: 1.05;
  letter-spacing: 0.05em;
  text-transform: uppercase;
}
.widget .is-divider {
  margin-top: 0.66em;
}

.is-divider {
  height: 3px;
  display: block;
  background-color: rgba(0, 0, 0, 0.1);
  margin: 1em 0 1em;
  width: 100%;
  max-width: 30px;
}
a {
  text-decoration: none;
}
::v-deep .v-menu__content {
  margin-top: 20px;
}
</style>
