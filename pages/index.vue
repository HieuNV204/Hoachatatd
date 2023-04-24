<template>
  <v-sheet>
    <v-sheet>
      <v-carousel height="800" hide-delimiters>
        <v-carousel-item
          src="https://hoachatdaiviet.com/wp-content/uploads/2022/05/background-chemistry_2.png"
          cover
        ></v-carousel-item>
        <v-carousel-item
          src="https://hoachatdaiviet.com/wp-content/uploads/2022/05/background-chemistry_3.jpeg"
          cover
        ></v-carousel-item>
        <v-carousel-item
          src="https://hoachatdaiviet.com/wp-content/uploads/2022/05/background-chemistry_4.png"
          cover
        ></v-carousel-item>
        <v-carousel-item
          src="https://hoachatdaiviet.com/wp-content/uploads/2022/05/background-for-chemistry_5.jpg"
          cover
        ></v-carousel-item>
      </v-carousel>
    </v-sheet>
    <v-sheet class="mt-4 d-flex align-center justify-center">
      <v-container style="max-width: 1300px">
        <v-row>
          <v-col md="5" class="mr-0 pr-0">
            <v-avatar rounded size="450px">
              <img
                alt="image"
                src="https://bcp.cdnchinhphu.vn/Uploaded/nguyenminhdiem/2021_08_02/hoachat.jpg"
              />
            </v-avatar>
          </v-col>
          <v-col md="7" class="ml-0 pl-0">
            <div class="tl">
              <p><strong>15 YEAR</strong></p>
              <p>LÀM VIỆC & SÁNG TẠO</p>
            </div>
            <div>
              <p class="mb-0"><b>Tại sao chọn Hóa chất An Thành Danh?</b></p>
              <p>15+ Năm kiến tạo và xây dựng niềm tin</p>
              <p class="text-red">NƠI TRAO GỬI NIỀM TIN</p>
            </div>
            <v-row class="mt-0 ml-0">
              <v-col md="4">
                <v-row>
                  <div class="icon-inner">
                    <img
                      alt="image"
                      src="https://hoachatdaiviet.com/wp-content/uploads/2022/05/636967286_636969908213651674.png"
                    />
                  </div>
                  <div class="icon-box-text last-reset">
                    <h3>500+</h3>
                    <p>Mã sản phẩm</p>
                  </div>
                </v-row>
              </v-col>
              <v-col md="4">
                <v-row>
                  <div class="icon-inner">
                    <img
                      alt="image"
                      src="	https://hoachatdaiviet.com/wp-content/uploads/2022/05/636967286_636969908321437839.png"
                    />
                  </div>
                  <div class="icon-box-text last-reset">
                    <h3>150+</h3>
                    <p>Nhân sự nhiệt huyết</p>
                  </div>
                </v-row>
              </v-col>
              <v-col md="4">
                <v-row>
                  <div class="icon-inner">
                    <img
                      alt="image"
                      src="https://hoachatdaiviet.com/wp-content/uploads/2022/05/636967286_636969908425503791.png"
                    />
                  </div>
                  <div class="icon-box-text last-reset">
                    <h3>100+</h3>
                    <p>Đối tác uy tín</p>
                  </div>
                </v-row>
              </v-col>
            </v-row>
            <p class="mt-4">
              Công ty HÓA CHẤT AN THÀNH DANH hoạt động trong lĩnh vực sản xuất,
              kinh doanh, xuất nhập khẩu hóa chất, phục vụ trong các ngành công
              nghiệp, là một trong những đơn vị đầu tiên về hóa chất tại Việt
              Nam.
            </p>
            <ul>
              <li>Hóa chất công nghiệp</li>
              <li>Hóa chất dung môi</li>
              <li>Hóa chất tẩy rửa</li>
              <li>Hóa dầu</li>
              <li>Hóa chất xử lý bề mặt kim loại...</li>
            </ul>
          </v-col>
        </v-row>
        <div class="col small-12 large-12" style="margin-top: 80px">
          <div class="col-inner text-center">
            <div class="container section-title-container">
              <h2 class="section-title section-title-center">
                <b></b>
                <span class="section-title-main">DANH MỤC SẢN PHẨM</span>
                <b></b>
              </h2>
            </div>
            <div class="row large-columns-8">
              <div
                v-for="obj in listCategory"
                :key="obj.id"
                class="product-category col"
              >
                <div class="col-inner">
                  <a>
                    <div class="box box-category has-hover box-normal">
                      <div class="box-image">
                        <div class="">
                          <img
                            :src="obj.image"
                            :alt="obj.title"
                            width="200"
                            height="200"
                          />
                        </div>
                      </div>
                      <div class="box-text text-center">
                        <div class="box-text-inner">
                          <h5 class="text-uppercase header-title">
                            {{ obj.title }}
                          </h5>
                          <p class="is-small text-capitalize count">
                            {{ obj.count }} Sản phẩm
                          </p>
                        </div>
                      </div>
                    </div>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </v-container>
    </v-sheet>
    <v-sheet class="bg section-bg1 fill bg-fill bg-loaded">
      <div class="col-inner">
        <div class="container section-title-container">
          <h2 class="section-title section-title-center mt-10">
            <b></b
            ><span class="section-title-main" style="color: rgb(255, 255, 255)"
              >SẢN PHẨM NỔI BẬT</span
            ><b></b>
          </h2>
        </div>
        <v-container style="max-width: 1100px">
          <v-carousel hide-delimiters>
            <v-carousel-item class="ml-8 mt-10">
              <v-row>
                <v-container style="max-width: 300px" class="col-inner">
                  <div class="badge-container absolute left top z-1"></div>
                  <div class="product-small box">
                    <div class="box-image">
                      <div class="image-fade_in_back">
                        <img
                          width="247"
                          height="247"
                          src="https://hoachatdaiviet.com/wp-content/uploads/2019/10/Bot-Tay-duong-Na2S2O4-Sodium-Hydrosunfite-3-247x247.jpg"
                        />
                      </div>
                    </div>
                    <div
                      class="box-text box-text-products text-center grid-style-2"
                    >
                      <div class="title-wrapper">
                        <p
                          class="text-uppercase is-smaller no-text-overflow is-smaller op-7 mb-0"
                          style="color: #f1f1f1"
                        >
                          phụ gia thực phẩm
                        </p>
                        <p style="color: #f1f1f1">
                          Tẩy Đường – Na2S2O4 – Sodium Hydrosunfite
                        </p>
                      </div>
                      <div class="price-wrapper">
                        <div class="read-more-custom">
                          <a
                            ><span>Xem chi tiết</span
                            ><i class="icon-angle-right"></i
                          ></a>
                        </div>
                      </div>
                    </div>
                  </div>
                </v-container>
                <v-container style="max-width: 300px" class="col-inner">
                  <div class="badge-container absolute left top z-1"></div>
                  <div class="product-small box">
                    <div class="box-image">
                      <div class="image-fade_in_back">
                        <img
                          width="247"
                          height="247"
                          src="https://hoachatdaiviet.com/wp-content/uploads/2022/11/TCCA-90-SHIKOKU-NHAT-2-247x247.png"
                        />
                      </div>
                    </div>
                    <div
                      class="box-text box-text-products text-center grid-style-2"
                    >
                      <div class="title-wrapper">
                        <p
                          class="text-uppercase is-smaller no-text-overflow is-smaller op-7 mb-0"
                          style="color: #f1f1f1"
                        >
                          Hóa Chất Công Nghiệp
                        </p>
                        <p style="color: #f1f1f1">TCCA 90% SHIKOKU NHẬT</p>
                      </div>
                      <div class="price-wrapper">
                        <div class="read-more-custom">
                          <a
                            ><span>Xem chi tiết</span
                            ><i class="icon-angle-right"></i
                          ></a>
                        </div>
                      </div>
                    </div>
                  </div>
                </v-container>
                <v-container style="max-width: 300px" class="col-inner">
                  <div class="badge-container absolute left top z-1"></div>
                  <div class="product-small box">
                    <div class="box-image">
                      <div class="image-fade_in_back">
                        <img
                          width="247"
                          height="247"
                          src="https://hoachatdaiviet.com/wp-content/uploads/2018/10/ig-ashitide-247x247.jpg"
                        />
                      </div>
                    </div>
                    <div
                      class="box-text box-text-products text-center grid-style-2"
                    >
                      <div class="title-wrapper">
                        <p
                          class="text-uppercase is-smaller no-text-overflow is-smaller op-7 mb-0"
                          style="color: #f1f1f1"
                        >
                          Phụ Gia Thực Phẩm
                        </p>
                        <p style="color: #f1f1f1">Chất điều vị IG Ashitide</p>
                      </div>
                      <div class="price-wrapper">
                        <div class="read-more-custom">
                          <a
                            ><span>Xem chi tiết</span
                            ><i class="icon-angle-right"></i
                          ></a>
                        </div>
                      </div>
                    </div>
                  </div>
                </v-container>
              </v-row>
            </v-carousel-item>
            <v-carousel-item class="ml-8 mt-10">
              <v-row>
                <v-container style="max-width: 300px" class="col-inner">
                  <div class="badge-container absolute left top z-1"></div>
                  <div class="product-small box">
                    <div class="box-image">
                      <div class="image-fade_in_back">
                        <img
                          width="247"
                          height="247"
                          src="https://hoachatdaiviet.com/wp-content/uploads/2022/01/WholeMilk-Powder-sua-bot-nguyen-kem-247x247.jpg"
                        />
                      </div>
                    </div>
                    <div
                      class="box-text box-text-products text-center grid-style-2"
                    >
                      <div class="title-wrapper">
                        <p
                          class="text-uppercase is-smaller no-text-overflow is-smaller op-7 mb-0"
                          style="color: #f1f1f1"
                        >
                          phụ gia thực phẩm
                        </p>
                        <p style="color: #f1f1f1">
                          Whole Milk Powder – Sữa bột nguyên kem
                        </p>
                      </div>
                      <div class="price-wrapper">
                        <div class="read-more-custom">
                          <a
                            ><span>Xem chi tiết</span
                            ><i class="icon-angle-right"></i
                          ></a>
                        </div>
                      </div>
                    </div>
                  </div>
                </v-container>
                <v-container style="max-width: 300px" class="col-inner">
                  <div class="badge-container absolute left top z-1"></div>
                  <div class="product-small box">
                    <div class="box-image">
                      <div class="image-fade_in_back">
                        <img
                          width="247"
                          height="247"
                          src="https://hoachatdaiviet.com/wp-content/uploads/2018/11/Chlorite-Nippon-Nhat-247x247.jpg"
                        />
                      </div>
                    </div>
                    <div
                      class="box-text box-text-products text-center grid-style-2"
                    >
                      <div class="title-wrapper">
                        <p
                          class="text-uppercase is-smaller no-text-overflow is-smaller op-7 mb-0"
                          style="color: #f1f1f1"
                        >
                          Hóa Chất Công Nghiệp
                        </p>
                        <p style="color: #f1f1f1">Chlorite Nippon</p>
                      </div>
                      <div class="price-wrapper">
                        <div class="read-more-custom">
                          <a
                            ><span>Xem chi tiết</span
                            ><i class="icon-angle-right"></i
                          ></a>
                        </div>
                      </div>
                    </div>
                  </div>
                </v-container>
                <v-container style="max-width: 300px" class="col-inner">
                  <div class="badge-container absolute left top z-1"></div>
                  <div class="product-small box">
                    <div class="box-image">
                      <div class="image-fade_in_back">
                        <img
                          width="247"
                          height="247"
                          src="https://hoachatdaiviet.com/wp-content/uploads/2020/04/tcca-200gam-dang-vien-bot-247x247.jpg"
                        />
                      </div>
                    </div>
                    <div
                      class="box-text box-text-products text-center grid-style-2"
                    >
                      <div class="title-wrapper">
                        <p
                          class="text-uppercase is-smaller no-text-overflow is-smaller op-7 mb-0"
                          style="color: #f1f1f1"
                        >
                          Hóa Chất xử lý nước
                        </p>
                        <p style="color: #f1f1f1">Bột Whey Powder</p>
                      </div>
                      <div class="price-wrapper">
                        <div class="read-more-custom">
                          <a
                            ><span>Xem chi tiết</span
                            ><i class="icon-angle-right"></i
                          ></a>
                        </div>
                      </div>
                    </div>
                  </div>
                </v-container>
              </v-row>
            </v-carousel-item>
            <v-carousel-item class="ml-8 mt-10">
              <v-row>
                <v-container style="max-width: 300px" class="col-inner">
                  <div class="badge-container absolute left top z-1"></div>
                  <div class="product-small box">
                    <div class="box-image">
                      <div class="image-fade_in_back">
                        <img
                          width="247"
                          height="247"
                          src="https://hoachatdaiviet.com/wp-content/uploads/2022/01/Bot-Whey-Powder-247x247.jpg"
                        />
                      </div>
                    </div>
                    <div
                      class="box-text box-text-products text-center grid-style-2"
                    >
                      <div class="title-wrapper">
                        <p
                          class="text-uppercase is-smaller no-text-overflow is-smaller op-7 mb-0"
                          style="color: #f1f1f1"
                        >
                          phụ gia thực phẩm
                        </p>
                        <p style="color: #f1f1f1">Bột Whey Powder</p>
                      </div>
                      <div class="price-wrapper">
                        <div class="read-more-custom">
                          <a
                            ><span>Xem chi tiết</span
                            ><i class="icon-angle-right"></i
                          ></a>
                        </div>
                      </div>
                    </div>
                  </div>
                </v-container>
                <v-container style="max-width: 300px" class="col-inner">
                  <div class="badge-container absolute left top z-1"></div>
                  <div class="product-small box">
                    <div class="box-image">
                      <div class="image-fade_in_back">
                        <img
                          width="247"
                          height="247"
                          src="https://hoachatdaiviet.com/wp-content/uploads/2019/07/clorin-org-247x247.jpg"
                        />
                      </div>
                    </div>
                    <div
                      class="box-text box-text-products text-center grid-style-2"
                    >
                      <div class="title-wrapper">
                        <p
                          class="text-uppercase is-smaller no-text-overflow is-smaller op-7 mb-0"
                          style="color: #f1f1f1"
                        >
                          Hóa Chất Công Nghiệp
                        </p>
                        <p style="color: #f1f1f1">Chlorine Ấn Độ 70% Organic</p>
                      </div>
                      <div class="price-wrapper">
                        <div class="read-more-custom">
                          <a
                            ><span>Xem chi tiết</span
                            ><i class="icon-angle-right"></i
                          ></a>
                        </div>
                      </div>
                    </div>
                  </div>
                </v-container>
                <v-container style="max-width: 300px" class="col-inner">
                  <div class="badge-container absolute left top z-1"></div>
                  <div class="product-small box">
                    <div class="box-image">
                      <div class="image-fade_in_back">
                        <img
                          width="247"
                          height="247"
                          src="https://hoachatdaiviet.com/wp-content/uploads/2019/10/Bot-Tay-duong-Na2S2O4-Sodium-Hydrosunfite-3-247x247.jpg"
                        />
                      </div>
                    </div>
                    <div
                      class="box-text box-text-products text-center grid-style-2"
                    >
                      <div class="title-wrapper">
                        <p
                          class="text-uppercase is-smaller no-text-overflow is-smaller op-7 mb-0"
                          style="color: #f1f1f1"
                        >
                          Phụ gia thực phẩm
                        </p>
                        <p style="color: #f1f1f1">
                          Tẩy Đường – Na2S2O4 – Sodium Hydrosunfite
                        </p>
                      </div>
                      <div class="price-wrapper">
                        <div class="read-more-custom">
                          <a
                            ><span>Xem chi tiết</span
                            ><i class="icon-angle-right"></i
                          ></a>
                        </div>
                      </div>
                    </div>
                  </div>
                </v-container>
              </v-row>
            </v-carousel-item>
          </v-carousel>
        </v-container>
      </div>
    </v-sheet>
    <v-sheet
      class="bg section-bg2 fill bg-fill bg-loaded"
      style="margin-top: 60px"
      min-height="800"
    >
      <div class="section-content relative">
        <div class="container section-title-container">
          <h2 class="section-title section-title-center mt-10">
            <b></b
            ><span class="section-title-main" style="color: rgb(255, 255, 255)"
              >NHÀ MÁY SẢN XUẤT</span
            ><b></b>
          </h2>
        </div>
        <v-container class="d-flex justify-center">
          <v-avatar
            rounded
            height="200"
            width="250"
            class="mr-10"
            style="margin-top: 150px"
          >
            <img
              alt="Avatar"
              src="https://hoachatdaiviet.com/wp-content/uploads/2022/05/background-chemistry_4-700x400.png"
            />
          </v-avatar>
          <v-avatar
            rounded
            height="200"
            width="250"
            class="mr-10"
            style="margin-top: 150px"
          >
            <img
              alt="Avatar"
              src="https://hoachatdaiviet.com/wp-content/uploads/2021/10/san-xuat-cloraminb-600x400.jpg"
            />
          </v-avatar>
          <v-avatar
            rounded
            height="200"
            width="250"
            class="mr-10"
            style="margin-top: 150px"
          >
            <img
              alt="Avatar"
              src="https://hoachatdaiviet.com/wp-content/uploads/2022/05/background-chemistry_2-700x400.png"
            />
          </v-avatar>
          <v-avatar
            rounded
            height="200"
            width="250"
            class="mr-10"
            style="margin-top: 150px"
          >
            <img
              alt="Avatar"
              src="https://hoachatdaiviet.com/wp-content/uploads/2022/05/Kho-hoa-chat-602x400.jpg"
            />
          </v-avatar>
          <v-avatar
            rounded
            height="200"
            width="250"
            class="mr-10"
            style="margin-top: 150px"
          >
            <img
              alt="Avatar"
              src="https://hoachatdaiviet.com/wp-content/uploads/2022/05/BQHC3-616x400-1.jpg"
            />
          </v-avatar>
        </v-container>
      </div>
    </v-sheet>
    <v-sheet>
      <v-row>
        <v-container class="d-flex justify-center" style="margin-top: 50px">
          <v-avatar rounded height="100" width="150" class="mr-10">
            <img
              alt="Avatar"
              src="https://hoachatdaiviet.com/wp-content/uploads/2018/08/van-minh.png"
            />
          </v-avatar>
          <v-avatar rounded height="100" width="150" class="mr-10">
            <img
              alt="Avatar"
              src="https://hoachatdaiviet.com/wp-content/uploads/2018/08/thien-phuoc-group.jpg"
            />
          </v-avatar>
          <v-avatar rounded height="100" width="150" class="mr-10">
            <img
              alt="Avatar"
              src="https://hoachatdaiviet.com/wp-content/uploads/2018/08/sike.jpg"
            />
          </v-avatar>
          <v-avatar rounded height="100" width="150" class="mr-10">
            <img
              alt="Avatar"
              src="https://hoachatdaiviet.com/wp-content/uploads/2018/08/nafoods-group.jpg"
            />
          </v-avatar>
          <v-avatar rounded height="100" width="150" class="mr-10">
            <img
              alt="Avatar"
              src="https://hoachatdaiviet.com/wp-content/uploads/2018/08/muong-thanh.jpg"
            />
          </v-avatar>
          <v-avatar rounded height="100" width="150" class="mr-10">
            <img
              alt="Avatar"
              src="https://hoachatdaiviet.com/wp-content/uploads/2018/08/gia-khanh.png"
            />
          </v-avatar>
        </v-container>
      </v-row>
    </v-sheet>
    <v-sheet style="background-color: rgb(250, 250, 250); margin-top: 33px">
      <v-row>
        <v-container
          class="d-flex justify-center justify-space-between"
          style="max-width: 1368px"
        >
          <v-col md="3">
            <div class="col-inner">
              <div class="icon-box featured-box icon-box-left text-left">
                <div class="icon-box-img" style="width: 60px">
                  <v-avatar rounded width="57" height="33">
                    <img
                      alt="Avatar"
                      src="https://hoachatdaiviet.com/wp-content/uploads/2022/05/636963609006924323.png"
                    />
                  </v-avatar>
                </div>
                <div class="icon-box-text last-reset">
                  <h4 class="item-title">VẬN CHUYỂN SIÊU TỐC</h4>
                  <p>Giao hàng với hầu hết các mặt hàng</p>
                </div>
              </div>
            </div>
          </v-col>
          <v-col md="3">
            <div class="col-inner">
              <div class="icon-box featured-box icon-box-left text-left">
                <div class="icon-box-img" style="width: 60px">
                  <v-avatar rounded width="57" height="58">
                    <img
                      alt="Avatar"
                      src="https://hoachatdaiviet.com/wp-content/uploads/2022/05/636963609132450554.png"
                    />
                  </v-avatar>
                </div>
                <div class="icon-box-text last-reset">
                  <h4 class="item-title">SẢN PHẨM ĐA DẠNG</h4>
                  <p>
                    Chúng tôi cung cấp các sản phẩm hóa chất, đa dạng về chủng
                    loại
                  </p>
                </div>
              </div>
            </div>
          </v-col>
          <v-col md="3">
            <div class="col-inner">
              <div class="icon-box featured-box icon-box-left text-left">
                <div class="icon-box-img" style="width: 60px">
                  <v-avatar rounded width="57" height="56">
                    <img
                      alt="Avatar"
                      src="https://hoachatdaiviet.com/wp-content/uploads/2022/05/636963609281522914.png"
                    />
                  </v-avatar>
                </div>
                <div class="icon-box-text last-reset">
                  <h4 class="item-title">HỆ THỐNG TOÀN QUỐC</h4>
                  <p>
                    Chúng tôi có nhiều nhà máy, kho xưởng, văn phòng trên toàn
                    quốc
                  </p>
                </div>
              </div>
            </div>
          </v-col>
          <v-col md="3">
            <div class="icon-box-left text-left">
              <div class="icon-box-img" style="width: 60px">
                <v-avatar rounded width="57" height="69">
                  <img
                    alt="Avatar"
                    src="https://hoachatdaiviet.com/wp-content/uploads/2022/05/636963609423332750.png"
                  />
                </v-avatar>
              </div>
              <div class="icon-box-text last-reset">
                <h4 class="item-title">UY TÍN HÀNG ĐẦU</h4>
                <p>Với hơn 15 năm kinh nghiệm trên thị trường Việt Nam</p>
              </div>
            </div>
          </v-col>
        </v-container>
      </v-row>
    </v-sheet>
  </v-sheet>
</template>

<script>
export default {
  name: "IndexPage",
  data: () => ({
    listCategory: [
      {
        id: 1,
        image:
          "https://hoachatdaiviet.com/wp-content/uploads/2022/05/ban-chay-nhat-247x247.gif",
        title: "Sản phẩm bán chạy",
        count: 26,
      },
      {
        id: 2,
        image:
          "https://hoachatdaiviet.com/wp-content/uploads/2022/05/melodylogistics-thu-tuc-nhap-khau-hoa-chat-1-247x247.jpg",
        title: "Hóa chất khác",
        count: 10,
      },
      {
        id: 3,
        image:
          "https://hoachatdaiviet.com/wp-content/uploads/2018/10/hoa-chat-phu-gia-thuc-pham-la-gi-247x247.jpg",
        title: "Phụ gia thực phẩm",
        count: 54,
      },
      {
        id: 4,
        image:
          "https://hoachatdaiviet.com/wp-content/uploads/2018/07/Phu-gia-tao-mau-thuc-pham-247x247.jpg",
        title: "Màu thực phẩm",
        count: 9,
      },
      {
        id: 5,
        image:
          "https://hoachatdaiviet.com/wp-content/uploads/2018/11/huong-lieu-tao-mui-247x247.jpg",
        title: "Hương liệu",
        count: 66,
      },
      {
        id: 6,
        image:
          "https://hoachatdaiviet.com/wp-content/uploads/2022/05/hoa-chat-cong-nghiep-co-rat-nhieu-ung-dung-trong-cuoc-song-247x247.jpg",
        title: "Hóa chất công nghiệp",
        count: 38,
      },
      {
        id: 7,
        image:
          "https://hoachatdaiviet.com/wp-content/uploads/2018/10/hoa-chat-the-nao-la-dung-moi-cong-nghiep-247x247.jpg",
        title: "Dung môi công nghiệp",
        count: 16,
      },
      {
        id: 8,
        image:
          "https://hoachatdaiviet.com/wp-content/uploads/2018/11/su-dung-cloramin-b-247x247.jpg",
        title: "Hóa chất tẩy rửa",
        count: 46,
      },
      {
        id: 9,
        image:
          "https://hoachatdaiviet.com/wp-content/uploads/2018/10/hoa-chat-hoa-chat-thuy-hai-san-la-gi-1-247x247.jpg",
        title: "Hóa chất thủy sản",
        count: 23,
      },
      {
        id: 10,
        image:
          "https://hoachatdaiviet.com/wp-content/uploads/2018/11/hoa-chat-xu-ly-nuoc-247x247.jpg",
        title: "Hóa chất xử lý nước",
        count: 41,
      },
    ],
  }),
};
</script>
<style scoped>
.tl {
  border-left: 8px solid #1a9fe6;
  padding-left: 12px;
  flex-shrink: 0;
  width: 40%;
}
.text-red {
  background-color: #1a9fe6;
  color: #fff;
  padding: 10px 20px;
  display: inline-block;
}
.tl strong {
  font-weight: bold;
  font-size: 40px;
  line-height: 30px;
  display: block;
  margin-bottom: 8px;
  position: relative;
  left: -4px;
  color: #ff8e95;
}
.icon-inner {
  width: 55px;
  min-width: 55px;
  height: 55px;
  border-radius: 50%;
  background-color: #1a9fe6;
  padding: 5px !important;
  margin-right: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.icon-box-text h3 {
  color: #1a9fe6;
  font-size: 22px;
  margin-bottom: 0px;
}
.section-title {
  position: relative;
  -js-display: flex;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -ms-flex-flow: row wrap;
  flex-flow: row wrap;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  width: 100%;
}
.section-title-center span {
  margin: 0 15px;
}
.section-title b {
  display: block;
  -webkit-box-flex: 1;
  -ms-flex: 1;
  flex: 1;
  height: 2px;
  opacity: 0.1;
  background-color: currentColor;
}
.is-small {
  font-size: 0.7em;
}
.section-bg1 {
  background-image: url(https://hoachatdaiviet.com/wp-content/uploads/2022/05/Kho-hoa-chat_2.jpg);
  background-size: 1800px 700px;
}
.box-text {
  padding-top: 0.7em;
  padding-bottom: 1.4em;
  position: relative;
  width: 100%;
  font-size: 0.9em;
}
.read-more-custom a {
  display: inline-flex;
  align-items: center;
  font-size: 15px;
  line-height: 24px;
  padding: 3px 16px 3px 21px;
  color: #fff;
  background-color: #1a9fe6;
  border-radius: 20px;
}
.no-text-overflow {
  white-space: nowrap;
  overflow: hidden;
  -o-text-overflow: ellipsis;
  text-overflow: ellipsis;
}
.op-7 {
  opacity: 0.7;
}
.is-smaller {
  font-size: 0.75em;
}
.section-bg2 {
  background-image: url(https://hoachatdaiviet.com/wp-content/uploads/2022/05/nha-may_2.jpg);
  background-position: 5% 40%;
}
.text-left {
  text-align: left;
}
.icon-box-left,
.icon-box-right {
  -js-display: flex;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -ms-flex-flow: row wrap;
  flex-flow: row;
  width: 100%;
}
.icon-box-left .icon-box-img + .icon-box-text {
  padding-left: 1em;
}
</style>
