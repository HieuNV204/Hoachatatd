<template>
  <v-sheet>
    <div id="wrapper">
      <div class="banner-page">
        <img
          class="banner-page_image"
          src="https://hoachatdaiviet.com/wp-content/themes/flatsome-child/img/banner.jpg"
        />
      </div>

      <main id="main" class="mt-4">
        <div class="page-wrapper page-right-sidebar">
          <div class="row">
            <div id="content" class="large-9 left col col-divided" role="main">
              <div class="page-inner">
                <h4>
                  Hóa Chất An Thành Danh sẽ giao hàng tận nơi nếu Quý khách có
                  yêu cầu khi đăng ký thông tin địa chỉ nhận hàng rõ ràng để
                  tránh thất lạc.
                </h4>
                <p>
                  Hàng sẽ được chuyển qua đường bưu điện, chành xe, các đơn vị
                  chuyển phát nhanh hoặc nhân viên của chúng tôi sẽ giao hàng
                  trực tiếp đến quý khách hàng.
                </p>
                <figure
                  id="attachment_2868"
                  aria-describedby="caption-attachment-2868"
                  style="width: 711px"
                  class="wp-caption aligncenter"
                >
                  <a
                    ><img
                      decoding="async"
                      class="size-medium wp-image-2868"
                      title="CHÍNH SÁCH GIAO HÀNG"
                      src="https://hoachatdaiviet.com/wp-content/uploads/2020/10/hoa-chatchinh-sach-giao-hang-711x400.jpg"
                      alt="CHÍNH SÁCH GIAO HÀNG"
                      width="711"
                      height="400"
                      srcset="
                        https://hoachatdaiviet.com/wp-content/uploads/2020/10/hoa-chatchinh-sach-giao-hang-711x400.jpg 711w,
                        https://hoachatdaiviet.com/wp-content/uploads/2020/10/hoa-chatchinh-sach-giao-hang-510x287.jpg 510w,
                        https://hoachatdaiviet.com/wp-content/uploads/2020/10/hoa-chatchinh-sach-giao-hang-768x432.jpg 768w,
                        https://hoachatdaiviet.com/wp-content/uploads/2020/10/hoa-chatchinh-sach-giao-hang-24x14.jpg    24w,
                        https://hoachatdaiviet.com/wp-content/uploads/2020/10/hoa-chatchinh-sach-giao-hang-36x20.jpg    36w,
                        https://hoachatdaiviet.com/wp-content/uploads/2020/10/hoa-chatchinh-sach-giao-hang-48x27.jpg    48w,
                        https://hoachatdaiviet.com/wp-content/uploads/2020/10/hoa-chatchinh-sach-giao-hang.jpg         800w
                      "
                      sizes="(max-width: 711px) 100vw, 711px"
                  /></a>
                  <figcaption
                    id="caption-attachment-2868"
                    class="wp-caption-text"
                  >
                    CHÍNH SÁCH GIAO HÀNG
                  </figcaption>
                </figure>
                <p>
                  <em
                    >*Việc tính phí tùy thuộc vào giá trị đơn hàng và địa điểm
                    giao hàng.</em
                  >
                </p>
                <p><em>Lưu ý:</em></p>
                <p>
                  <em>*&nbsp;</em>Thời gian giao hàng: An Thành Danh sẽ giao
                  hàng cho Quý khách từ 02 – 04 giờ đối với khách hàng khu vực
                  Hà Nội, HCM, Nha Trang kể từ lúc Quý khách xác nhận đặt hàng
                  với chúng tôi. Từ 1-5 ngày đối với khách hàng tại các tỉnh tuỳ
                  theo phương thức giao hàng mà Quý khách lựa chọn (trực tiếp
                  hoặc qua đường bưu điện).
                </p>
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
  name: "SupportTransport",
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
.wp-caption .wp-caption-text {
  padding: 0.4em;
  font-size: 0.9em;
  background: rgba(0, 0, 0, 0.05);
  font-style: italic;
}

.wp-caption-text {
  text-align: center;
}
</style>
