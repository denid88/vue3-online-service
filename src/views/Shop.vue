<template>
  <MainHeader />
  <AppBreadcrumbs />


  <!--shop  area start-->
  <div class="shop_area shop_reverse mt-50 mb-50">
    <div class="container">
      <div class="row">
        <div class="col-lg-3 col-md-12">
          <!--sidebar widget start-->
          <aside class="sidebar_widget">
            <div class="widget_inner">
              <div class="widget_list widget_categories">
                <h3>Women</h3>
                <ul>
                  <li class="widget_sub_categories sub_categories1"><a href="javascript:void(0)">Shoes</a>
                    <ul class="widget_dropdown_categories dropdown_categories1">
                      <li><a href="#">Document</a></li>
                      <li><a href="#">Dropcap</a></li>
                      <li><a href="#">Dummy Image</a></li>
                      <li><a href="#">Dummy Text</a></li>
                      <li><a href="#">Fancy Text</a></li>
                    </ul>
                  </li>
                  <li class="widget_sub_categories sub_categories2"><a href="javascript:void(0)">Bags</a>
                    <ul class="widget_dropdown_categories dropdown_categories2">
                      <li><a href="#">Flickr</a></li>
                      <li><a href="#">Flip Box</a></li>
                      <li><a href="#">Cocktail</a></li>
                      <li><a href="#">Frame</a></li>
                      <li><a href="#">Flickrq</a></li>
                    </ul>
                  </li>
                  <li class="widget_sub_categories sub_categories3"><a href="javascript:void(0)">Clothing</a>
                    <ul class="widget_dropdown_categories dropdown_categories3">
                      <li><a href="#">Platform Beds</a></li>
                      <li><a href="#">Storage Beds</a></li>
                      <li><a href="#">Regular Beds</a></li>
                      <li><a href="#">Sleigh Beds</a></li>
                      <li><a href="#">Laundry</a></li>
                    </ul>
                  </li>
                </ul>
              </div>
              <div class="widget_list widget_filter">
                <h3>Filter by price</h3>
                <form action="#">
                  <div id="slider-range"></div>
                  <button type="submit">Filter</button>
                  <input type="text" name="text" id="amount" />

                </form>
              </div>
              <div class="widget_list widget_color">
                <h3>Select By Color</h3>
                <ul>
                  <li>
                    <a href="#">Black  <span>(6)</span></a>
                  </li>
                  <li>
                    <a href="#"> Blue <span>(8)</span></a>
                  </li>
                  <li>
                    <a href="#">Brown <span>(10)</span></a>
                  </li>
                  <li>
                    <a href="#"> Green <span>(6)</span></a>
                  </li>
                  <li>
                    <a href="#">Pink <span>(4)</span></a>
                  </li>

                </ul>
              </div>
              <div class="widget_list widget_color">
                <h3>Select By SIze</h3>
                <ul>
                  <li>
                    <a href="#">S  <span>(6)</span></a>
                  </li>
                  <li>
                    <a href="#"> M <span>(8)</span></a>
                  </li>
                  <li>
                    <a href="#">L <span>(10)</span></a>
                  </li>
                  <li>
                    <a href="#"> XL <span>(6)</span></a>
                  </li>
                  <li>
                    <a href="#">XLL <span>(4)</span></a>
                  </li>

                </ul>
              </div>
              <div class="widget_list widget_manu">
                <h3>Manufacturer</h3>
                <ul>
                  <li>
                    <a href="#">Brake Parts <span>(6)</span></a>
                  </li>
                  <li>
                    <a href="#">Accessories <span>(10)</span></a>
                  </li>
                  <li>
                    <a href="#">Engine Parts <span>(4)</span></a>
                  </li>
                  <li>
                    <a href="#">hermes <span>(10)</span></a>
                  </li>
                  <li>
                    <a href="#">louis vuitton <span>(8)</span></a>
                  </li>

                </ul>
              </div>
              <div class="widget_list tags_widget">
                <h3>Product tags</h3>
                <div class="tag_cloud">
                  <a href="#">Men</a>
                  <a href="#">Women</a>
                  <a href="#">Watches</a>
                  <a href="#">Bags</a>
                  <a href="#">Dress</a>
                  <a href="#">Belt</a>
                  <a href="#">Accessories</a>
                  <a href="#">Shoes</a>
                </div>
              </div>
              <div class="widget_list banner_widget">
                <div class="banner_thumb">
                  <a href="#"><img src="assets/img/bg/banner17.jpg" alt=""></a>
                </div>
              </div>
            </div>
          </aside>
          <!--sidebar widget end-->
        </div>
        <div class="col-lg-9 col-md-12">
          <!--shop wrapper start-->
          <!--shop toolbar start-->
          <div class="shop_toolbar_wrapper">
            <div class="shop_toolbar_btn">

              <button data-role="grid_3" type="button" class="active btn-grid-3" data-toggle="tooltip" title="3"></button>

              <button data-role="grid_4" type="button"  class=" btn-grid-4" data-toggle="tooltip" title="4"></button>

              <button data-role="grid_list" type="button"  class="btn-list" data-toggle="tooltip" title="List"></button>
            </div>
            <div class=" niceselect_option">
              <form class="select_option" action="#">
                <select name="orderby" id="short">

                  <option selected value="1">Sort by average rating</option>
                  <option  value="2">Sort by popularity</option>
                  <option value="3">Sort by newness</option>
                  <option value="4">Sort by price: low to high</option>
                  <option value="5">Sort by price: high to low</option>
                  <option value="6">Product Name: Z</option>
                </select>
              </form>
            </div>
            <div class="page_amount">
              <p>Showing 1–9 of 21 results</p>
            </div>
          </div>
          <!--shop toolbar end-->
          <ProductsList />


          <div class="shop_toolbar t_bottom">
            <div class="pagination">
              <ul>
                <li class="current">1</li>
                <li><a href="#">2</a></li>
                <li><a href="#">3</a></li>
                <li class="next"><a href="#">next</a></li>
                <li><a href="#">>></a></li>
              </ul>
            </div>
          </div>
          <!--shop toolbar end-->
          <!--shop wrapper end-->
        </div>
      </div>
    </div>
  </div>
  <!--shop  area end-->
  <MainFooter />

  <!-- modal area start-->
  <div class="modal fade" id="modal_box" tabindex="-1" role="dialog"  aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered" role="document">
      <div class="modal-content">
        <button type="button" class="close" data-bs-dismiss="modal" aria-label="Close">
          <span aria-hidden="true"><i class="icon-x"></i></span>
        </button>
        <div class="modal_body">
          <div class="container">
            <div class="row">
              <div class="col-lg-5 col-md-5 col-sm-12">
                <div class="modal_tab">
                  <div class="tab-content product-details-large">
                    <div class="tab-pane fade show active" id="tab1" role="tabpanel" >
                      <div class="modal_tab_img">
                        <a href="#"><img src="assets/img/product/productbig1.jpg" alt=""></a>
                      </div>
                    </div>
                    <div class="tab-pane fade" id="tab2" role="tabpanel">
                      <div class="modal_tab_img">
                        <a href="#"><img src="assets/img/product/productbig2.jpg" alt=""></a>
                      </div>
                    </div>
                    <div class="tab-pane fade" id="tab3" role="tabpanel">
                      <div class="modal_tab_img">
                        <a href="#"><img src="assets/img/product/productbig3.jpg" alt=""></a>
                      </div>
                    </div>
                    <div class="tab-pane fade" id="tab4" role="tabpanel">
                      <div class="modal_tab_img">
                        <a href="#"><img src="assets/img/product/productbig4.jpg" alt=""></a>
                      </div>
                    </div>
                  </div>
                  <div class="modal_tab_button">
                    <ul class="nav product_navactive owl-carousel" role="tablist">
                      <li >
                        <a class="nav-link active" data-toggle="tab" href="#tab1" role="tab" aria-controls="tab1" aria-selected="false"><img src="assets/img/product/product1.jpg" alt=""></a>
                      </li>
                      <li>
                        <a class="nav-link" data-toggle="tab" href="#tab2" role="tab" aria-controls="tab2" aria-selected="false"><img src="assets/img/product/product6.jpg" alt=""></a>
                      </li>
                      <li>
                        <a class="nav-link button_three" data-toggle="tab" href="#tab3" role="tab" aria-controls="tab3" aria-selected="false"><img src="assets/img/product/product2.jpg" alt=""></a>
                      </li>
                      <li>
                        <a class="nav-link" data-toggle="tab" href="#tab4" role="tab" aria-controls="tab4" aria-selected="false"><img src="assets/img/product/product7.jpg" alt=""></a>
                      </li>

                    </ul>
                  </div>
                </div>
              </div>
              <div class="col-lg-7 col-md-7 col-sm-12">
                <div class="modal_right">
                  <div class="modal_title mb-10">
                    <h2>Donec Ac Tempus</h2>
                  </div>
                  <div class="modal_price mb-10">
                    <span class="new_price">$64.99</span>
                    <span class="old_price" >$78.99</span>
                  </div>
                  <div class="modal_description mb-15">
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia iste laborum ad impedit pariatur esse optio tempora sint ullam autem deleniti nam in quos qui nemo ipsum numquam, reiciendis maiores quidem aperiam, rerum vel recusandae </p>
                  </div>
                  <div class="variants_selects">
                    <div class="variants_size">
                      <h2>size</h2>
                      <select class="select_option">
                        <option selected value="1">s</option>
                        <option value="1">m</option>
                        <option value="1">l</option>
                        <option value="1">xl</option>
                        <option value="1">xxl</option>
                      </select>
                    </div>
                    <div class="variants_color">
                      <h2>color</h2>
                      <select class="select_option">
                        <option selected value="1">purple</option>
                        <option value="1">violet</option>
                        <option value="1">black</option>
                        <option value="1">pink</option>
                        <option value="1">orange</option>
                      </select>
                    </div>
                    <div class="modal_add_to_cart">
                      <form action="#">
                        <input min="1" max="100" step="2" value="1" type="number">
                        <button type="submit">add to cart</button>
                      </form>
                    </div>
                  </div>
                  <div class="modal_social">
                    <h2>Share this product</h2>
                    <ul>
                      <li class="facebook"><a href="#"><i class="fa fa-facebook"></i></a></li>
                      <li class="twitter"><a href="#"><i class="fa fa-twitter"></i></a></li>
                      <li class="pinterest"><a href="#"><i class="fa fa-pinterest"></i></a></li>
                      <li class="google-plus"><a href="#"><i class="fa fa-google-plus"></i></a></li>
                      <li class="linkedin"><a href="#"><i class="fa fa-linkedin"></i></a></li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!--<AppTemplate title="List of products" />-->
</template>

<script>
import AppTemplate from '../components/ui/AppTemplate'
import MainHeader from '../components/header/MainHeader'
import AppBreadcrumbs from '../components/ui/AppBreadcrumps'
import ProductsList from '../components/shop/ProductsList'
import MainFooter from '../components/footer/MainFooter'
export default {
  name: 'Home',
  components: {
    AppBreadcrumbs,
    AppTemplate,
    MainHeader,
    ProductsList,
    MainFooter
  }
}
</script>
