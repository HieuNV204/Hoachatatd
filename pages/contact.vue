<template>
  <v-sheet>
    <div id="wrapper">
      <div class="banner-page">
        <img
          class="banner-page_image"
          src="https://hoachatdaiviet.com/wp-content/themes/flatsome-child/img/banner.jpg"
        />
      </div>

      <main id="main" class="">
        <div class="row page-wrapper">
          <div id="content" class="large-12 col" role="main">
            <header class="entry-header text-center">
              <h1 class="entry-title">Liên Hệ</h1>
              <div class="is-divider medium"></div>
            </header>

            <div class="entry-content">
              <h3 style="text-align: center">Hóa Chất An Thành Danh</h3>
              <p>
                <img
                  decoding="async"
                  class="aligncenter wp-image-793"
                  src="https://hoachatdaiviet.com/wp-content/uploads/2019/03/hoa-chat-van-chuyen-hoa-chat-cong-nghiep-an-toan-can-luu-y-nhung-yeu-to-nao.jpg"
                  alt=""
                  width="813"
                  height="543"
                />
              </p>
              <div class="row row-small" id="row-433637138">
                <div id="col-42448268" class="col medium-6 small-12 large-6">
                  <div class="col-inner">
                    <h3>
                      <span style="font-size: 90%"
                        >An Thành Danh hoạt động với tiêu chí mang đến lợi ích
                        tối đa cho khách hàng, lấy chữ tín làm tiền để phát
                        triển.</span
                      >
                    </h3>
                    <h3>
                      <span style="font-size: 90%"
                        >SẢN PHẨM CHẤT LƯỢNG TỐT</span
                      >
                    </h3>
                    <p>
                      <span style="font-size: 90%"
                        >Chúng tôi cam kết 100% sản phẩm bán trên website đều có
                        nguồn gốc, xuất xứ rõ ràng, đảm bảo tiêu chuẩn chất
                        lượng, và đảm bảo sức khỏe người tiêu dùng. Nói không
                        với hàng giả, hàng nhái, hàng kém chất lượng.</span
                      >
                    </p>
                  </div>
                </div>

                <div id="col-275035131" class="col medium-3 small-12 large-3">
                  <div class="col-inner">
                    <h4><span style="font-size: 90%">ĐỊA CHỈ</span></h4>
                    <p>
                      <strong>CÔNG TY TNHH AN THÀNH DANH</strong><br />
                      <strong>Mã số thuế: 0110055890<br /> </strong
                      ><strong>Địa chỉ đăng ký kinh doanh</strong>: Xóm 3, thôn
                      Văn Trai, xã Văn Phú, huyện Thường Tín, Thành phố Hà Nội
                    </p>
                    <h4><span style="font-size: 90%">SỐ ĐIỆN THOẠI</span></h4>
                    <p><strong>0876819988</strong></p>
                  </div>
                </div>

                <div id="col-1156534858" class="col medium-3 small-12 large-3">
                  <div class="col-inner">
                    <h3>
                      <span style="font-size: 90%">THỜI GIAN LÀM VIỆC</span>
                    </h3>
                    <p>
                      <span style="font-size: 90%"
                        >Thứ Hai đến Thứ Bảy: 8:00 – 19:00</span
                      ><br />
                      <span style="font-size: 90%">
                        Chủ Nhật: 8:00 – 12:00</span
                      >
                    </p>
                    <h3><span style="font-size: 90%">KẾT NỐI</span></h3>
                    <p>
                      <span style="font-size: 90%"
                        >Email: congtyanthanhdanh@gmail.com</span
                      >
                    </p>
                    <div
                      class="social-icons follow-icons full-width text-left"
                      style="font-size: 77%"
                    >
                      <a
                        href="#"
                        target="_blank"
                        data-label="Facebook"
                        rel="noopener noreferrer nofollow"
                        class="icon primary button circle facebook tooltip"
                        title="Follow on Facebook"
                        aria-label="Follow on Facebook"
                        ><i class="icon-facebook"></i></a
                      ><a
                        href="#"
                        target="_blank"
                        rel="noopener noreferrer nofollow"
                        data-label="Instagram"
                        class="icon primary button circle instagram tooltip"
                        title="Follow on Instagram"
                        aria-label="Follow on Instagram"
                        ><i class="icon-instagram"></i></a
                      ><a
                        href="#"
                        target="_blank"
                        rel="noopener noreferrer nofollow"
                        data-label="Pinterest"
                        class="icon primary button circle pinterest tooltip"
                        title="Follow on Pinterest"
                        aria-label="Follow on Pinterest"
                        ><i class="icon-pinterest"></i></a
                      ><a
                        href="#"
                        target="_blank"
                        rel="noopener noreferrer nofollow"
                        data-label="YouTube"
                        class="icon primary button circle youtube tooltip"
                        title="Follow on YouTube"
                        aria-label="Follow on YouTube"
                        ><i class="icon-youtube"></i
                      ></a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </main>
    </div>
  </v-sheet>
</template>

<script>
export default {
  name: "Contact",
};
</script>
<style scoped lang="scss">
.banner-page {
  display: block;
  position: relative;
  z-index: 1;
  overflow: hidden;
  height: 500px;
  &_image {
    position: absolute;
    z-index: 1;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    background-position: 45% 40%;
  }
}
.entry-content {
  padding-top: 1.5em;
  padding-bottom: 1.5em;
}
.aligncenter {
  clear: both;
  display: block;
  margin: 0 auto;
}
.entry-content ul li,
.entry-summary ul li,
.col-inner ul li {
  margin-left: 1.3em;
}

li {
  margin-bottom: 0.6em;
}
a {
  color: #334862;
  text-decoration: none;
}
b,
strong {
  font-weight: bolder;
}
</style>
