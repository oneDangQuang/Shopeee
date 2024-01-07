<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Shopee</title>
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">
	<link rel="stylesheet" href="index/css/base.css">
	<link rel="stylesheet" href="index/css/main.css">
	<link rel="stylesheet" href="index/css/grid.css">
	<link rel="stylesheet" href="index/css/responsive.css">
	<link rel="stylesheet" href="index/fonts/fontawesome/css/all.min.css">
	<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">

</head>
<body>
	<div class="app">
		<!-- header -->
		<header class="header">
			<div class="grid wide">

				<!-- header navbar -->
				<nav class="header__navbar hide-on-mobile-tablet">

					<!-- header navbar left -->
					<ul class="header__navbar-list">
						<li class="header__navbar-item header__navbar-item-has-qr header__navbar-item--separate">
							Tải ứng dụng
							<div class="header__qr">
								<img src="image/QRcode.png" alt="QR code" class="header__qr-img">
								<div class="header__qr-apps">
									<a class="header__qr-link">
										<img src="image/CH_play.png" alt="CH Play" class="header__qr-download-img">
									</a>
									<a class="header__qr-link">
										<img src="image/apstore.png" alt="Apstore" class="header__qr-download-img">
									</a>
								</div>
							</div>
						</li>
						<li class="header__navbar-item">
							<span class="header__navbar-item-no-pointer">Kết nối</span>
							<a href="#" class="header__navbar-icon-link">
								<i class="header__navbar-icon fab fa-facebook"></i>
							</a>
							<a href="#" class="header__navbar-icon-link">
								<i class="header__navbar-icon fab fa-instagram"></i>
							</a>
						</li>
					</ul>
					<!--rnd header navbar left -->

					<!-- header navbar right -->
					<ul class="header__navbar-list">
						<li class="header__navbar-item header__navbar-item-has-notity">
							<a href="#" class="header__navbar-item-link">
								<i class="header__navbar-icon far fa-bell"></i>
								Thông báo
							</a>
							<div class="header__notify">
								<header class="header__notify-header">
									<h3>Thông báo mới</h3>
								</header>
								<ul class="header__notify-list">
									<li class="header__notify-item header__notify-item-viewed">
										<a href="#" class="header__notify-link">
											<img src="image/sp_01.jpg" alt="" class="header__notify-img">
											<div class="header__notify-info">
												<div class="header__notify-name">Chiếc quần quốc dân</div>
												<div class="header__notify-descrition">Chiếc quần hot trend trên nền tảng MXH TikTok được giới trẻ săn đón</div>
											</div>
										</a>
									</li>
									<li class="header__notify-item header__notify-item-viewed">
										<a href="#" class="header__notify-link">
											<img src="image/sp_00.png" alt="" class="header__notify-img">
											<div class="header__notify-info">
												<div class="header__notify-name">Lễ hội ngày 1/1 săn sale sập sàn</div>
												<div class="header__notify-descrition">Ngày 1/1, săn sale Shoppe ngập tràn. Lễ hội thời trang - Siêu hội phong cách</div>
											</div>
										</a>
									</li>
									<li class="header__notify-item header__notify-item-viewed">
										<a href="#" class="header__notify-link">
											<img src="image/sp_06.jpg" alt="" class="header__notify-img">
											<div class="header__notify-info">
												<div class="header__notify-name">Lý do bạn nên dùng sữa rửa mặt thường xuyên</div>
												<div class="header__notify-descrition">Khi di chuyển bên ngoài cần phải vệ sinh sạch sẽ bề mặt da để tránh các hiện tượng như dị ứng, thô ráp hay da đen xạm</div>
											</div>
										</a>
									</li>
									<li class="header__notify-item">
										<a href="#" class="header__notify-link">
											<img src="image/sp_05.jpg" alt="" class="header__notify-img">
											<div class="header__notify-info">
												<div class="header__notify-name">Giảm giá sốc</div>
												<div class="header__notify-descrition">Iphone 13 pro max màu Alipine green (mới ra mắt) giảm giá sốc trong đợt sale ngày 6/6 này.</div>
											</div>
										</a>
									</li>
								</ul>
								<div class="header__notify-footer">
									<a href="#" class="header__notity-footer-link">Xem tất cả</a>
								</div>
							</div>
						</li>
						<li class="header__navbar-item">
							<a href="#" class="header__navbar-item-link">
								<i class="header__navbar-icon far fa-question-circle"></i>
								Hỗ Trợ
							</a>
						</li>	

						<!-- <li class="header__navbar-item header__navbar-item--strong header__navbar-item--separate">Đăng ký</li>
							<li class="header__navbar-item header__navbar-item--strong">Đăng nhập</li> -->

							<li class="header__navbar-item header__navbar-user">
								<img src="image/Avt.jpg" class="header__navbar-user-img">
								<span class="header__navbar-user-name">Trần Đăng Quang</span>

								<ul class="header__navbar-user-menu">
									<li class="header__navbar-user-item">
										<a href="#">Tài khoản của tôi</a>
									</li>
									<li class="header__navbar-user-item">
										<a href="#">Đơn mua</a>
									</li>
									<li class="header__navbar-user-item header__navbar-user-item--separate">
										<a href="#">Đăng xuất</a>
									</li>
								</ul>
							</li>		
						</ul>
						<!--end header navbar right -->
					</nav>

					<!-- end header-navbar -->


					<!-- header-search -->
					<div class="header-with-search">
						
						<label for="header-bars-input" class="header__bars-btn">
							<i class="fas fa-bars header__bars-icon"></i>
						</label>
						
						<input type="checkbox" class="header__bars-input" id="header-bars-input">
						<div class="header__mobile">
							<!-- <div class="header__mobile-search-wrap">
								<div class="header__mobile-search">
									<input type="text" class="header__mobile-search-btn" placeholder="Tìm kiếm sản phẩm...">
									<button class="header__search-moblie-btn">
										<i class="fas fa-search header__search-mobile-btn-icon"></i>
									</button>
								</div>
							</div> -->
							<ul class="header__mobile-list">
								<li class="header__mobile-item">
									<a href="" class="header__mobile-link">Trang chủ</a>
								</li>

								<li class="header__mobile-item">
									<a href="" class="header__mobile-link">Giỏ hàng</a>
								</li>
								
								<li class="header__mobile-item">
									<a href="" class="header__mobile-link">Đăng ký</a>
								</li>

								<li class="header__mobile-item">
									<a href="" class="header__mobile-link">Đăng nhập</a>
								</li>

							</ul>
							<label for="header-bars-input">
								<i class="fas fa-times header__mobile-close"></i>
							</label>
							
						</div>

						<label for="header-bars-input" class="modal">
							<div class="modal__overlay"></div>
						</label>
						<!-- logo -->
						<div class="header__logo">
							<a href="#" class="header__logo-link">
								<img class="header__logo-img" src="image/logo.jpg" alt="">
							</a>
						</div>

						<!-- end logo -->

						<!-- search -->
						<div class="header__search hide-on-mobile">
							<div class="header__search-input-wrap">
								<input type="text" class="header__search-input" placeholder="Tìm kiếm sản phẩm theo tên, danh mục...">

								<div class="header__search-history">
									<h3 class="header__search-history-heading">Lịch sử tìm kiếm</h3>
									<ul class="header__search-history-list">
										<li class="header__search-history-item">
											<a href="#">Quần Baggy nam</a>
										</li>
										<li class="header__search-history-item">
											<a href="#">Iphone 13 Pro Max</a>
										</li>
										<li class="header__search-history-item">
										    <a href="#">Sữa rửa mặt SVR</a>
										</li>
										<li class="header__search-history-item">
										    <a href="#">Túi đeo chéo nam</a>
										</li>
									</ul>
								</div>
							</div>
							<div class="header__search-select">
								<span class="header__search-select-label">
									Trong shop
								</span>
								<i class="fas fa-chevron-down header__search-select-icon"></i>

								<ul class="header__search-option">
									<li class="header__search-option-item header__search-option-item--active">
										<span>Trong shop</span>
										<i class="fas fa-check "></i>
									</li>

									<li class="header__search-option-item">
										<span>Ngoài shop</span>
										<i class="fas fa-check "></i>
									</li>
								</ul>
							</div>

							<button class="header__search-btn">
								<i class="fas fa-search header__search-btn-icon"></i>
							</button>

						</div>
						<!--end search -->

						<!-- cart -->
						<div class="header__cart">
							<div class="header__cart-wrap">
								<span class="header__cart-notice">
									3
								</span>
								<i class="fas fa-shopping-cart header__cart-icon"></i>
								<div class="header__cart-list">
									<!-- no cart: header__cart-list--no-cart -->
									<img src="image/no_cart.png" alt="" class="header__cart-no-cart-img">
									<p class="header__cart-no-cart-msg">
										Chưa có sản phẩm
									</p>

									<h4 class="header__cart-heading">Sản phẩn mới thêm</h4>
									<ul class="header__cart-list-item">
										<li class="header__cart-item">
											<img src="image/sp_05.jpg" class="header__cart-img">
											<div class="header__cart-item-info">
												<div class="header__cart-item-head">
													<h5 class="header__cart-item-name">Apple iphone 13 Pro Max 128GB</h5>
													<div class="header__cart-item-price-wrap">
														<span class="header__cart-item-price">28.590.000</span>
														<span class="header__cart-item-multiply">x</span>
														<span class="header__cart-item-qnt">1</span>
													</div>
												</div>
												<div class="header__cart-item-body">
													<span class="header__cart-item-description">
														Phân loại: <span class="header__cart-item-classify">Điện thoại</span>
													</span>
													<span class="header__cart-item-remove">Xóa</span>
												</div>
											</div>
										</li>
										<li class="header__cart-item">
											<img src="image/sp_03.jpg" class="header__cart-img">
											<div class="header__cart-item-info">
												<div class="header__cart-item-head">
													<h5 class="header__cart-item-name">Áo Polo Plastic WNS
													</h5>
													<div class="header__cart-item-price-wrap">
														<span class="header__cart-item-price">330.000</span>
														<span class="header__cart-item-multiply">x</span>
														<span class="header__cart-item-qnt">2</span>
													</div>
												</div>
												<div class="header__cart-item-body">
													<span class="header__cart-item-description">
														Phân loại: <span class="header__cart-item-classify">Xanh lá,XL</span>
													</span>
													<span class="header__cart-item-remove">Xóa</span>
												</div>
											</div>
										</li>
										<li class="header__cart-item">
											<img src="image/sp_06.jpg" class="header__cart-img">
											<div class="header__cart-item-info">
												<div class="header__cart-item-head">
													<h5 class="header__cart-item-name">Sữa rửa mặt SVR</h5>
													<div class="header__cart-item-price-wrap">
														<span class="header__cart-item-price">415.000</span>
														<span class="header__cart-item-multiply">x</span>
														<span class="header__cart-item-qnt">3</span>
													</div>
												</div>
												<div class="header__cart-item-body">
													<span class="header__cart-item-description">
														Phân loại: <span class="header__cart-item-classify">Bigsize - 400ml</span>
													</span>
													<span class="header__cart-item-remove">Xóa</span>
												</div>
											</div>
										</li>
									</ul>
									<button class="btn btn--primary header__cart-view-cart">
										Xem giỏ hàng
									</button>
								</div>
							</div>
						</div>
						<!--end cart -->
					</div>

					<!--end header-search -->
				</div>
			</div>
			<ul class="header__sort-bar">
				<li class="header__sort-item">
					<a href="#" class="header__sort-link">Liên quan</a>
				</li>

				<li class="header__sort-item header__sort-item--active">
					<a href="#" class="header__sort-link">Mới nhất</a>
				</li>

				<li class="header__sort-item">
					<a href="#" class="header__sort-link">Bán chạy</a>
				</li>

				<li class="header__sort-item">
					<a href="#" class="header__sort-link">Giá</a>
				</li>
			</ul>

		</header>
		<!--end header -->

		<!-- container -->
		<div class="app__container">
			<div class="grid wide">
				<div class="row sm-gutter app__content">

					<!-- aside -->
					<div class="col l-2 m-0 c-0">
						<nav class="category">
							<h3 class="category__heading">
								<i class="fas fa-list-ul category__heading-icon"></i>
							Theo danh mục</h3>
							<ul class="category-list">
								<li class="category-item">
									<a href="#" class="category-item__link">Điện thoại</a>
								</li>
								<li class="category-item catgory-item--active">
									<a href="#" class="category-item__link">Thời trang nam</a>
								</li>
								<li class="category-item">
									<a href="#" class="category-item__link">Giày thể thao</a>
								</li>
								<li class="category-item">
									<a href="#" class="category-item__link">Ốp điện thoại</a>
								</li>
								<li class="category-item">
									<a href="#" class="category-item__link">Túi đeo chéo</a>
								</li>
								<li class="category-item">
									<a href="#" class="category-item__link">Sữa rửa mặt</a>
								</li>
								<li class="category-item">
									<a href="#" class="category-item__link">Áo phông</a>
								</li>
								<li class="category-item">
									<a href="#" class="category-item__link">Giá đỡ laptop</a>
								</li>
								<li class="category-item">
									<a href="#" class="category-item__link">Quần âu</a>
								</li>
							</ul>
						</nav>
					</div>
					<!-- end aside -->

					<!-- article -->
					<div class="col l-10 m-12 c-12">

						<!-- home filter -->
						<div class="home-filter hide-on-mobile-tablet">
							<span class="home-filter__label">
								Sắp xếp theo
							</span>
							<button class="btn home-filter__btn">Liên quan</button>
							<button class="btn btn--primary home-filter__btn">Mới nhất</button>
							<button class="btn btn--primary home-filter__btn">Bán chạy</button>

							<div class="select-input">
								<span class="select-input__label">Giá</span>
								<i class="fas fa-chevron-down select-input__icon"></i>
								<ul class="select-input__list">
									<li class="select-input__item">
										<a href="#" class="select-input__link">Giá: Thấp đến cao</a>
									</li>
									<li class="select-input__item">
										<a href="#" class="select-input__link">Giá: Cao đến thấp</a>
									</li>

								</ul>
							</div>

							<div class="home-filter__page">
								<span class="home-filter__page-num">
									<span class="home-filter__page-current">1</span>/
									<span class="home-filter__page-total">10</span>
								</span>
								<div class="home-filter__page-control">
									<a href="#" class="home-filter__page-btn home-filter__page-btn--disable">
										<i class="fas fa-angle-left home-filter__page-icon"></i>
									</a>
									<a href="#" class="home-filter__page-btn">
										<i class="fas fa-angle-right home-filter__page-icon"></i>
									</a>
								</div>
							</div>
						</div>

						<!--end home filter -->
						
						<nav class="mobile-category">
							<ul class="mobile-category__list">
								<li class="mobile-category__item"
									<a href="#" class="mobile-category__link">Giày thể thao nam</a>
								</li>
								<li class="mobile-category__item">
									<a href="#" class="mobile-category__link">Túi đeo chéo nam</a>
								</li>
								<li class="mobile-category__item">
									<a href="#" class="mobile-category__link">Quần jean baggy</a>
								</li>
								<li class="mobile-category__item">
									<a href="#" class="mobile-category__link">Áo polo</a>
								</li>
								<li class="mobile-category__item">
									<a href="#" class="mobile-category__link">Giày sneaker thể thao</a>
								</li>
								<li class="mobile-category__item">
									<a href="#" class="mobile-category__link">Ốp điện thoại</a>
								</li>
								<li class="mobile-category__item">
									<a href="#" class="mobile-category__link">Sữa rửa mặt</a>
								</li>
								<li class="mobile-category__item">
									<a href="#" class="mobile-category__link">Iphone 13 pro max</a>
								</li>
								<li class="mobile-category__item">
									<a href="#" class="mobile-category__link">Giá đỡ laptop</a>
								</li>
								<li class="mobile-category__item">
									<a href="#" class="mobile-category__link">Quần ống suông</a>
								</li>
							</ul>
						</nav>
						<!-- product -->
						<div class="home-product">
							<div class="row sm-gutter">
								<!-- product item -->
								<div class="col l-2-4 m-4 c-6">
									<a class="home-product-item" href="#">
										<div class="home-product-item-img" style="background-image: url(image/sp_01.jpg)">
										</div>
										<h4 class="home-product-item-name">Quần jean baggy nam ống rộng màu trắng</h4>
										<div class="home-product-item__price">
											<span class="home-product-item__price-old">₫155.000 - ₫169.000</span>
											<span class="home-product-item__price-current">₫144.000</span>
										</div>
										<div class="home-product-item__action">
											<span class="home-product-item__like home-product-item__like--liked">
												<i class="far fa-heart home-product-item-icon-like-empty"></i>
												<i class="fas fa-heart home-product-item-icon home-product-item-icon-like-fill"></i>
											</span>
											<div class="home-product-item__rating">
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
											</div>
											<span class="home-product-item__sold">Đã bán 4,2k</span>
										</div>
										<div class="home-product-item__origin">
											<span class="home-product-item__brand">VN</span>
											<span class="home-product-item__origin-name">Hà Nội</span>
										</div>
										<div class="home-product-item__favourite">
											<i class="fas fa-check"></i>
											<span>Yêu thích</span>
										</div>
										<div class="home-product-item__sale-off">
											<span class="home-product-item__sale-off-percent">10%</span>
											<span class="home-product-item__sale-off-label">GIẢM</span>
										</div>
									</a>
								</div>
								<div class="col l-2-4 m-4 c-6">
									<a class="home-product-item" href="#">
										<div class="home-product-item-img" style="background-image: url(image/sp_02.jpg)">
										</div>
										<h4 class="home-product-item-name">Quần âu nam Hàn Quốc dáng baggy suông đen</h4>
										<div class="home-product-item__price">
											<span class="home-product-item__price-old">₫259.000 - ₫280.000</span>
											<span class="home-product-item__price-current">₫149.000</span>
										</div>
										<div class="home-product-item__action">
											<span class="home-product-item__like home-product-item__like--liked">
												<i class="far fa-heart home-product-item-icon-like-empty"></i>
												<i class="fas fa-heart home-product-item-icon home-product-item-icon-like-fill"></i>
											</span>
											<div class="home-product-item__rating">
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
											</div>
											<span class="home-product-item__sold">Đã bán 1,3k</span>
										</div>
										<div class="home-product-item__origin">
											<span class="home-product-item__brand">VN</span>
											<span class="home-product-item__origin-name">Hà Nội</span>
										</div>
										<div class="home-product-item__favourite">
											<i class="fas fa-check"></i>
											<span>Yêu thích</span>
										</div>
										<div class="home-product-item__sale-off">
											<span class="home-product-item__sale-off-percent">47%</span>
											<span class="home-product-item__sale-off-label">GIẢM</span>
										</div>
									</a>
								</div>
								<div class="col l-2-4 m-4 c-6">
									<a class="home-product-item" href="#">
										<div class="home-product-item-img" style="background-image: url(image/sp_03.jpg)">
										</div>
										<h4 class="home-product-item-name">Áo polo Plastic WNS</h4>
										<div class="home-product-item__price">
											<span class="home-product-item__price-old">₫439.000 - ₫449.000 </span>
											<span class="home-product-item__price-current">₫330.000</span>
										</div>
										<div class="home-product-item__action">
											<span class="home-product-item__like home-product-item__like--liked">
												<i class="far fa-heart home-product-item-icon-like-empty"></i>
												<i class="fas fa-heart home-product-item-icon home-product-item-icon-like-fill"></i>
											</span>
											<div class="home-product-item__rating">
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
											</div>
											<span class="home-product-item__sold">Đã bán 803</span>
										</div>
										<div class="home-product-item__origin">
											<span class="home-product-item__brand">VN</span>
											<span class="home-product-item__origin-name">Hà Nội</span>
										</div>
										<div class="home-product-item__favourite">
											<i class="fas fa-check"></i>
											<span>Yêu thích</span>
										</div>
										<div class="home-product-item__sale-off">
											<span class="home-product-item__sale-off-percent">25%</span>
											<span class="home-product-item__sale-off-label">GIẢM</span>
										</div>
									</a>
								</div>
								<div class="col l-2-4 m-4 c-6">
									<a class="home-product-item" href="#">
										<div class="home-product-item-img" style="background-image: url(image/sp_04.jpg)">
										</div>
										<h4 class="home-product-item-name">Túi Đeo chéo nam hoạ tiết Gudi</h4>
										<div class="home-product-item__price">
											<span class="home-product-item__price-old">đ469.000 - ₫499.000</span>
											<span class="home-product-item__price-current">₫345.000</span>
										</div>
										<div class="home-product-item__action">
											<span class="home-product-item__like home-product-item__like--liked">
												<i class="far fa-heart home-product-item-icon-like-empty"></i>
												<i class="fas fa-heart home-product-item-icon home-product-item-icon-like-fill"></i>
											</span>
											<div class="home-product-item__rating">
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
											</div>
											<span class="home-product-item__sold">Đã bán 902</span>
										</div>
										<div class="home-product-item__origin">
											<span class="home-product-item__brand">VN</span>
											<span class="home-product-item__origin-name">Hồ Chí Minh</span>
										</div>
										<div class="home-product-item__favourite">
											<i class="fas fa-check"></i>
											<span>Yêu thích</span>
										</div>
										<div class="home-product-item__sale-off">
											<span class="home-product-item__sale-off-percent">20%</span>
											<span class="home-product-item__sale-off-label">GIẢM</span>
										</div>
									</a>
								</div>
								<div class="col l-2-4 m-4 c-6">
									<a class="home-product-item" href="#">
										<div class="home-product-item-img" style="background-image: url(image/sp_05.jpg)">
										</div>
										<h4 class="home-product-item-name">Apple iphone 13 Pro Max 128GB</h4>
										<div class="home-product-item__price">
											<span class="home-product-item__price-old">₫33.990.000</span>
											<span class="home-product-item__price-current">₫28.590.000</span>
										</div>
										<div class="home-product-item__action">
											<span class="home-product-item__like home-product-item__like--liked">
												<i class="far fa-heart home-product-item-icon-like-empty"></i>
												<i class="fas fa-heart home-product-item-icon home-product-item-icon-like-fill"></i>
											</span>
											<div class="home-product-item__rating">
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
											</div>
											<span class="home-product-item__sold">Đã bán 3,5k</span>
										</div>
										<div class="home-product-item__origin">
											<span class="home-product-item__brand">VN</span>
											<span class="home-product-item__origin-name">Hà Nội</span>
										</div>
										<div class="home-product-item__favourite">
											<i class="fas fa-check"></i>
											<span>Yêu thích</span>
										</div>
										<div class="home-product-item__sale-off">
											<span class="home-product-item__sale-off-percent">15%</span>
											<span class="home-product-item__sale-off-label">GIẢM</span>
										</div>
									</a>
								</div>
								<div class="col l-2-4 m-4 c-6">
									<a class="home-product-item" href="#">
										<div class="home-product-item-img" style="background-image: url(image/sp_06.jpg)">
										</div>
										<h4 class="home-product-item-name">Sữa rửa mặt SVR SEBIACLEAR Gel</h4>
										<div class="home-product-item__price">
											<span class="home-product-item__price-old">₫468.00 - ₫479.000</span>
											<span class="home-product-item__price-current">đ415.000</span>
										</div>
										<div class="home-product-item__action">
											<span class="home-product-item__like home-product-item__like--liked">
												<i class="far fa-heart home-product-item-icon-like-empty"></i>
												<i class="fas fa-heart home-product-item-icon home-product-item-icon-like-fill"></i>
											</span>
											<div class="home-product-item__rating">
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
											</div>
											<span class="home-product-item__sold">Đã bán 2,2k</span>
										</div>
										<div class="home-product-item__origin">
											<span class="home-product-item__brand">VN</span>
											<span class="home-product-item__origin-name">Hồ Chí MInh</span>
										</div>
										<div class="home-product-item__favourite">
											<i class="fas fa-check"></i>
											<span>Yêu thích</span>
										</div>
										<div class="home-product-item__sale-off">
											<span class="home-product-item__sale-off-percent">7%</span>
											<span class="home-product-item__sale-off-label">GIẢM</span>
										</div>
									</a>
								</div>
								<div class="col l-2-4 m-4 c-6">
									<a class="home-product-item" href="#">
										<div class="home-product-item-img" style="background-image: url(image/sp_07.jpg)">
										</div>
										<h4 class="home-product-item-name">Ốp điện thoại TPU silicon mềm hình gấu thích hợp iphone 7 8 Plus</h4>
										<div class="home-product-item__price">
											<span class="home-product-item__price-old">đ16.000 - ₫69.000</span>
											<span class="home-product-item__price-current">₫12.000 - ₫49.500</span>
										</div>
										<div class="home-product-item__action">
											<span class="home-product-item__like home-product-item__like--liked">
												<i class="far fa-heart home-product-item-icon-like-empty"></i>
												<i class="fas fa-heart home-product-item-icon home-product-item-icon-like-fill"></i>
											</span>
											<div class="home-product-item__rating">
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
											</div>
											<span class="home-product-item__sold">Đã bán 198</span>
										</div>
										<div class="home-product-item__origin">
											<span class="home-product-item__brand">Shoppe</span>
											<span class="home-product-item__origin-name">Nước ngoài</span>
										</div>
										<div class="home-product-item__favourite">
											<i class="fas fa-check"></i>
											<span>Yêu thích</span>
										</div>
										<div class="home-product-item__sale-off">
											<span class="home-product-item__sale-off-percent">5%</span>
											<span class="home-product-item__sale-off-label">GIẢM</span>
										</div>
									</a>
								</div>
								<div class="col l-2-4 m-4 c-6">
									<a class="home-product-item" href="#">
										<div class="home-product-item-img" style="background-image: url(image/sp_08.jpg)">
										</div>
										<h4 class="home-product-item-name">Kệ, Giá đỡ Laptop và Macbook thông minh bằng gỗ cao cấp</h4>
										<div class="home-product-item__price">
											<span class="home-product-item__price-old">₫150.000 - ₫170.000</span>
											<span class="home-product-item__price-current">₫78.000 - ₫88.000</span>
										</div>
										<div class="home-product-item__action">
											<span class="home-product-item__like home-product-item__like--liked">
												<i class="far fa-heart home-product-item-icon-like-empty"></i>
												<i class="fas fa-heart home-product-item-icon home-product-item-icon-like-fill"></i>
											</span>
											<div class="home-product-item__rating">
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
											</div>
											<span class="home-product-item__sold">Đã bán 2k</span>
										</div>
										<div class="home-product-item__origin">
											<span class="home-product-item__brand">VN</span>
											<span class="home-product-item__origin-name">Đà Nẵng</span>
										</div>
										<div class="home-product-item__favourite">
											<i class="fas fa-check"></i>
											<span>Yêu thích</span>
										</div>
										<div class="home-product-item__sale-off">
											<span class="home-product-item__sale-off-percent">40%</span>
											<span class="home-product-item__sale-off-label">GIẢM</span>
										</div>
									</a>
								</div>
								<div class="col l-2-4 m-4 c-6">
									<a class="home-product-item" href="#">
										<div class="home-product-item-img" style="background-image: url(image/sp_11.jpg)">
										</div>
										<h4 class="home-product-item-name">Giày sneaker thể thao da nam cao cấp</h4>
										<div class="home-product-item__price">
											<span class="home-product-item__price-old">đ3.790.000</span>
											<span class="home-product-item__price-current">₫2.999.000</span>
										</div>
										<div class="home-product-item__action">
											<span class="home-product-item__like home-product-item__like--liked">
												<i class="far fa-heart home-product-item-icon-like-empty"></i>
												<i class="fas fa-heart home-product-item-icon home-product-item-icon-like-fill"></i>
											</span>
											<div class="home-product-item__rating">
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
											</div>
											<span class="home-product-item__sold">Đã bán 1,4k</span>
										</div>
										<div class="home-product-item__origin">
											<span class="home-product-item__brand">VN</span>
											<span class="home-product-item__origin-name">Hà Nội</span>
										</div>
										<div class="home-product-item__favourite">
											<i class="fas fa-check"></i>
											<span>Yêu thích</span>
										</div>
										<div class="home-product-item__sale-off">
											<span class="home-product-item__sale-off-percent">30%</span>
											<span class="home-product-item__sale-off-label">GIẢM</span>
										</div>
									</a>
								</div>
								<div class="col l-2-4 m-4 c-6">
									<a class="home-product-item" href="#">
										<div class="home-product-item-img" style="background-image: url(image/sp_10.jpg)">
										</div>
										<h4 class="home-product-item-name">Áo thun VEGSIVIR - WITH SINCERITY</h4>
										<div class="home-product-item__price">
											<span class="home-product-item__price-old">đ250.000 - đ279.000</span>
											<span class="home-product-item__price-current">đ189.000</span>
										</div>
										<div class="home-product-item__action">
											<span class="home-product-item__like home-product-item__like--liked">
												<i class="far fa-heart home-product-item-icon-like-empty"></i>
												<i class="fas fa-heart home-product-item-icon home-product-item-icon-like-fill"></i>
											</span>
											<div class="home-product-item__rating">
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
												<i class="fas fa-star home-product-item__star--gold"></i>
											</div>
											<span class="home-product-item__sold">Đã bán 4,1k </span>
										</div>
										<div class="home-product-item__origin">
											<span class="home-product-item__brand">VN</span>
											<span class="home-product-item__origin-name">Hà Nội</span>
										</div>
										<div class="home-product-item__favourite">
											<i class="fas fa-check"></i>
											<span>Yêu thích</span>
										</div>
										<div class="home-product-item__sale-off">
											<span class="home-product-item__sale-off-percent">30%</span>
											<span class="home-product-item__sale-off-label">GIẢM</span>
										</div>
									</a>
								</div>

							</div>
						</div>
						<!--end product -->

						<!-- pagination -->
						<ul class="pagination home-product__pagination">
							<li class="pagination-item">
								<a href="#" class="pagination-item__link">
									<i class="pagination-item__icon fas fa-angle-left"></i>
								</a>
							</li>

							<li class="pagination-item pagination-item--active">
								<a href="#" class="pagination-item__link">1</a>
							</li>
							<li class="pagination-item">
								<a href="#" class="pagination-item__link">2</a>
							</li>
							<li class="pagination-item">
								<a href="#" class="pagination-item__link">3</a>
							</li>
							<li class="pagination-item">
								<a href="#" class="pagination-item__link">4</a>
							</li>
							<li class="pagination-item">
								<a href="#" class="pagination-item__link">5</a>
							</li>
							<li class="pagination-item">
								<a href="#" class="pagination-item__link">...</a>
							</li>
							<li class="pagination-item">
								<a href="#" class="pagination-item__link">10</a>
							</li>

							<li class="pagination-item">
								<a href="#" class="pagination-item__link">
									<i class="pagination-item__icon fas fa-angle-right"></i>
								</a>
							</li>
						</ul>
						<!--end pagination -->
					</div>
					<!--end article -->
				</div>
			</div>
		</div>
		<!--end container -->

		<!-- footer -->
		<footer class="footer">
			<div class="grid wide">
				<div class="grid__row">
					<div class="col l-2-4 m-4 c-6">
						<h3 class="footer__heading">Chăm sóc khách hàng</h3>
						<ul class="footer-list">
							<li class="footer-item">
								<a href="#" class="footer-item__link">Trung Tâm Trợ Giúp</a>
							</li>
							<li class="footer-item">
							    <a href="#" class="footer-item__link">Shoppe Blog</a>
							</li>
							<li class="footer-item">
								<a href="#" class="footer-item__link">Shopee Mail</a>
							</li>
							<li class="footer-item">
								<a href="#" class="footer-item__link">Hướng Dẫn Mua Hàng</a>
							</li>
							<li class="footer-item">
							    <a href="#" class="footer-item__link">Hướng Dẫn Bán Hàng</a>
							</li>
							<li class="footer-item">
							    <a href="#" class="footer-item__link">Thanh Toán</a>
							</li>
							<li class="footer-item">
							    <a href="#" class="footer-item__link">Vận Chuyển</a>
							</li>
							<li class="footer-item">
							    <a href="#" class="footer-item__link">Hoàn Hàng & Trả Tiền</a>
							</li>
							<li class="footer-item">
							    <a href="#" class="footer-item__link">Chăm Sóc Khách Hàng</a>
							</li>
							<li class="footer-item">
							    <a href="#" class="footer-item__link">Chính Sách Bảo Hành</a>
							</li>
						</ul>
					</div>
					<div class="col l-2-4 m-4 c-6">
						<h3 class="footer__heading">Về Shoppe</h3>
						<ul class="footer-list">
							<li class="footer-item">
								<a href="#" class="footer-item__link">Giới Thiệu Về Shoppe Việt Nam</a>
							</li>
							<li class="footer-item">
								<a href="#" class="footer-item__link">Tuyển Dụng</a>
							</li>
							<li class="footer-item">
								<a href="#" class="footer-item__link">Điều Khoản Shoppe</a>
							</li>
							<li class="footer-item">
							    <a href="#" class="footer-item__link">Chính Sách Bảo Mật</a>
							</li>
							<li class="footer-item">
							    <a href="#" class="footer-item__link">Chính Hãng</a>
							</li>
							<li class="footer-item">
							    <a href="#" class="footer-item__link">Kênh Người Bán</a>
							</li>
							<li class="footer-item">
							    <a href="#" class="footer-item__link">Flash Sales</a>
							</li>
							<li class="footer-item">
							    <a href="#" class="footer-item__link">Liên Hệ Với Truyền Thông</a>
							</li>
						</ul>
					</div>
					<div class="col l-2-4 m-4 c-6">
						<h3 class="footer__heading">Theo Dõi Chúng Tôi</h3>
						<ul class="footer-list">
							<li class="footer-item">
								<a href="#" class="footer-item__link">
									<i class="fab fa-facebook footer-item__icon"></i>
									Facebook
								</a>
							</li>
							<li class="footer-item">
								<a href="#" class="footer-item__link">
									<i class="fab fa-instagram footer-item__icon"></i>
									Instagram
								</a>
							</li>
							<li class="footer-item">
								<a href="#" class="footer-item__link">
									<i class="fab fa-linkedin footer-item__icon"></i>
								Linkedin</a>
							</li>
						</ul>
					</div>
					<div class="col l-2-4 m-4 c-6">
						<h3 class="footer__heading">Danh mục</h3>
						<ul class="footer-list">
							<li class="footer-item">
								<a href="#" class="footer-item__link">Thời Trang</a>
							</li>
							<li class="footer-item">
								<a href="#" class="footer-item__link">Đồ Công Nghệ</a>
							</li>
							<li class="footer-item">
								<a href="#" class="footer-item__link">Mĩ Phẩm</a>
							</li>
							<li class="footer-item">
							    <a href="#" class="footer-item__link">Phụ Kiện</a>
							</li>
						</ul>
					</div>
					<div class="col l-2-4 m-8 c-6">
						<h3 class="footer__heading">Tải ứng dụng Shoppe ngay thôi</h3>
						<div class="footer__download">
							<img src="image/qrcode.png" class="footer__download-qr">
							<div class="footer__download-apps">
								<a href="#" class="footer__download-app-link">
									<img src="image/ch_play.png" class="footer__download-app-img">
								</a>

								<a href="#" class="footer__download-app-link">
									<img src="image/apstore.png" class="footer__download-app-img">
								</a>
							</div>
						</div>

					</div>
				</div>
			</div>
			
		</footer>

		<!--end footer -->
	</div>
	
	</body>
	</html>
