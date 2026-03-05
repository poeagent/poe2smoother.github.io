
<!doctype html>
<html lang="en" xmlns="https://www.w3.org/1999/xhtml" xmlns:fb="https://ogp.me/ns/fb#">

<head>
	<meta charset="utf-8">
	<title>PoeSmoother Online Store</title>

	<meta name="csrf_token" content="" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<meta name="description" content="Browse & buy online from PoeSmoother">

	<!-- Google / Search Engine Tags -->
	<meta itemprop="name" content="PoeSmoother Online Store">
	<meta itemprop="description" content="Browse & buy online from PoeSmoother" />

	<link rel="canonical" href="index.html" />

	<!-- Custom Google Verification. TO DO: Move this to the platform -->
	

	<!-- Custom Google Verification. TO DO: Move this to the platform -->
	
	<!-- Facebook Meta Tags -->
	<meta property="og:type" content="website" />
	<meta property="og:title" content="PoeSmoother Online Store" />
	<meta property="og:description" content="Browse & buy online from PoeSmoother" />
			<meta property="og:image" content="https://img.shoprocket.io/images/fit=cover,quality=75,w=270,h=270/66ed5e0ed15e2772044385-green-girl.jpg" />
	
	<!-- Twitter Meta Tags -->
	<meta name="twitter:card" content="summary" />
	<meta name="twitter:title" content="PoeSmoother Online Store" />
	<meta name="twitter:description" content="Browse & buy online from PoeSmoother" />
			<meta name="twitter:image" content="https://img.shoprocket.io/images/fit=cover,quality=75,w=270,h=270/66ed5e0ed15e2772044385-green-girl.jpg" />
			<link rel="shortcut icon" href="https://img.shoprocket.io/images/fit=cover,quality=75,w=32,h=32/66ed5f5436f9d097189542-48.ico">
	
	<!-- cover image preload -->
	
	<style type="text/css">
		html:root {
			--sr-theme-store-name: #666666;
			--sr-theme-embed-buy-button-color: #ffffff;
			--sr-theme-embed-buy-button-background-color: #233642;
			--sr-theme-embed-name-color: #314d5d;
			--sr-theme-embed-price-color: #2d2d2d;
			--sr-theme-embed-summary-color: #777777;
			--sr-theme-embed-view-button-color: #ffffff;
			--sr-theme-embed-view-button-background-color: #233642;
			--sr-theme-modal-cart-button-color: #ffffff;
			--sr-theme-modal-cart-button-background-color: #2b2b2b;
			--sr-theme-embed-background-color: #ffffff;
			--sr-theme-modal-background-color: #ffffff;
			--sr-theme-cart-trigger-color: #000000;
			--sr-theme-cart-trigger-text-color: #000000;
			--sr-theme-cart-trigger-background-color: #ffffff;
			--sr-theme-cart-trigger-counter-background-color: #000000;
			--sr-theme-cart-trigger-counter-color: #ffffff;
			--sr-theme-cart-background-color: #ffffff;
			--sr-theme-cart-button-background-color: #233642;
			--sr-theme-cart-button-color: #ffffff;
			--sr-theme-cart-links-text-color: #f8981d;
			--sr-theme-cart-body-text-color: #2b3e51;
			--sr-theme-cart-border-color: #ececec;
			--sr-theme-modal-button-color: #ffffff;
			--sr-theme-modal-button-background: #233642;
			--sr-theme-modal-name-color: #333;
			--sr-theme-modal-price-color: #777777;
			--sr-theme-modal-summary-color: #777777;
			--sr-theme-modal-active-tab-background-color: #f5f5f5;
		}

		body {
			/*Need to update this to actual var*/
			background: #ffffff;
			padding: 0;
			margin: 0;
			font-family: "Open Sans", Helvetica, Arial, sans-serif;
			font-size: 17px;
			font-weight: 400;
			line-height: 20px;
		}

		h1 {
			margin: 0;
			padding: 20px;
			text-align: center;
			font-family: Arial, Helvetica, sans-serif;
			color: #333;
		}

		a,
		a:hover,
		a:active,
		a:visited {
			font-weight: bold;
			color: inherit;
			text-decoration: none;
		}

		.logo {
			margin: 0 auto;
			position: relative;
			display: block;
			max-width: 125px;
			border-radius: 100%;
			margin-top: -62px;
			border: 5px solid #ffffff;
			background: #fff;
		}

		ul.social-icons {
			max-width: 100%;
			display: flex;
			gap: 10px;
			list-style: none;
			text-align: center;
			justify-content: center;
			margin: 0 auto;
			padding: 20px;
			font-size: 20px;
			flex-wrap: wrap;
			align-items: center;
		}

		ul.social-icons:empty {
			display: none;
		}

		ul.social-icons li:hover {
			opacity: 0.75;
		}

		ul.social-icons li svg {
			fill: #666666;
			width: 20px;
		}

		#newsletter-signup {
			margin: 20px auto;
			display: block;
			text-align: center;
			width: 350px;
			max-width: 90%;
			display: flex;
			justify-content: center;
			background: #fff;
			padding: 0;
			border-radius: 50px;
			padding: 5px;
			align-items: center;
			border: 1px solid #eee;
		}

		#newsletter-signup input {
			margin-left: 10px;
			padding: 10px;
			border: 0;
			width: 100%;
			outline: none;
		}

		#newsletter-signup button {
			height: fit-content;
			border: 0;
			border-radius: 50px;
			padding: 8px;
			background-color: var(--sr-theme-embed-buy-button-background-color);
			color: var(--sr-theme-embed-buy-button-color);
			cursor: pointer;
		}

		#newsletter-signup button span {
			display: flex;
		}

		#newsletter-signup button svg {
			width: 20px;
			fill: var(--sr-theme-embed-buy-button-color);
		}

		#newsletter-signup .btn-text {
			display: block;
			padding: 2px 8px;
		}

		#newsletter-signup button .signup-loading {
			animation: spin 2s linear infinite;
		}

		#signup-error-message:empty {
			display: none;
		}

		#signup-error-message {
			display: block;
			margin: 0 auto;
			width: fit-content;
			position: relative;
		}

		@keyframes spin {
			0% {
				transform: rotate(0deg);
			}

			100% {
				transform: rotate(360deg);
			}
		}

		body .sr-footer-logo {
			opacity: 0;
		}

		body .sr-element.sr-products {
			min-height: 400px;
		}

		body .sr-related-products-wrapper {
			min-height: auto;
		}

		body .sr-products .sr-item .sr-item-info {
			padding: 0 10px 10px 10px;
		}

		hr {
			width: 50px;
			border: 0;
			border-bottom: 3px solid;
			padding-top: 1.5rem;
			margin-bottom: 1.5rem;
			border-color: #666666;
		}

		.sr-hide {
			display: none !important;
		}

		.powered {
			left: 10px;
			bottom: 10px;
			padding: 10px;
			border-radius: 10px;
			width: fit-content;
		}

		.sr-logo {
			width: 144px;
		}

		.cover-image-wrapper {
			height: 300px;
			overflow: hidden;
			align-items: center;
			display: flex;
			background-size: cover;
			background-repeat: no-repeat;
			background-position: center;
		}

		.cover-image-wrapper {
			height: 100px;
		}

		.cover-image-wrapper picture {
			width: 100%;
		}

		.cover-image-wrapper img {
			width: 100%;
		}

		.logo-image-wrapper {
			text-align: center;
		}

		.logo-image-wrapper a {
			display: inline-block;
		}

		#signup-error-message,
		.store-intro,
		.store-bottom-text {
			padding: 20px;
			text-align: center;
			display: block;
			max-width: 1100px;
			margin: 0 auto;
			line-height: 28px;
		}

		.hs-store-name {
			color: #666666;
			line-height: 50px;
		}

		.store-intro {
			color: #666666;
		}

		.store-bottom-text {
			color: #666666;
		}

			</style>

	
	<script type="text/javascript">
		window.SR = {
			'API_ENDPOINT': 'https://api.shoprocket.io/'
		};
		window.SR.storefront_xhr = window.SR.API_ENDPOINT + "storefront/v1/stores/" + "sr_live_pk_36fec20aa341629de1987702b121e402dc88/";
	</script>
</head>

<body>
	<div class="cover-image-wrapper">
			</div>

			<div class="logo-image-wrapper">
							<a href="https://poesmoother.eu/">
					<img width="125px" height="125px" alt="PoeSmoother" class="logo" src="https://img.shoprocket.io/images/fit=cover,quality=75,w=270,h=270/66ed5e0ed15e2772044385-green-girl.jpg">
				</a>
					</div>
			<ul class="social-icons">
							<li><a name="discord" title="Join us on Discord" href="https://discord.gg/TwSWjsC6yG" target="_blank" class="social-icon">
						<svg viewBox="0 0 640 512" xmlns="http://www.w3.org/2000/svg">
							<path d="m524.531 69.836a1.5 1.5 0 0 0 -.764-.7 485.065 485.065 0 0 0 -119.686-37.106 1.816 1.816 0 0 0 -1.923.91 337.461 337.461 0 0 0 -14.9 30.6 447.848 447.848 0 0 0 -134.426 0 309.541 309.541 0 0 0 -15.135-30.6 1.89 1.89 0 0 0 -1.924-.91 483.689 483.689 0 0 0 -119.688 37.107 1.712 1.712 0 0 0 -.788.676c-76.229 113.838-97.111 224.877-86.867 334.541a2.016 2.016 0 0 0 .765 1.375 487.666 487.666 0 0 0 146.825 74.189 1.9 1.9 0 0 0 2.063-.676 348.2 348.2 0 0 0 30.037-48.842 1.86 1.86 0 0 0 -1.019-2.588 321.173 321.173 0 0 1 -45.868-21.853 1.885 1.885 0 0 1 -.185-3.126c3.082-2.309 6.166-4.711 9.109-7.137a1.819 1.819 0 0 1 1.9-.256c96.229 43.917 200.41 43.917 295.5 0a1.812 1.812 0 0 1 1.924.233c2.944 2.426 6.027 4.851 9.132 7.16a1.884 1.884 0 0 1 -.162 3.126 301.407 301.407 0 0 1 -45.89 21.83 1.875 1.875 0 0 0 -1 2.611 391.055 391.055 0 0 0 30.014 48.815 1.864 1.864 0 0 0 2.063.7 486.048 486.048 0 0 0 147.062-74.186 1.882 1.882 0 0 0 .765-1.352c12.264-126.783-20.532-236.912-86.934-334.541zm-302.04 267.744c-28.972 0-52.844-26.587-52.844-59.239s23.409-59.241 52.844-59.241c29.665 0 53.306 26.82 52.843 59.239 0 32.654-23.41 59.241-52.843 59.241zm195.38 0c-28.971 0-52.843-26.587-52.843-59.239s23.409-59.241 52.843-59.241c29.667 0 53.307 26.82 52.844 59.239 0 32.654-23.177 59.241-52.844 59.241z" />
						</svg>
					</a></li>
					</ul>
			<div class="store-intro">
			<p>PayPal</p>		</div>
			<hr>
	
	<div class="sr-element sr-products" data-embed="multiple_products">
		<script type="application/json" data-config="embed">
			{"publishable_key":"sr_live_pk_36fec20aa341629de1987702b121e402dc88","options":{"products_to_display":"categorized","categories":["games"],"image_dimension_value":"fit","image_aspect_ratio":"auto","button_style":"standard","variation_style":"on_hover","open_product_in":"popup","button_position":"inline","product_default_sorting_order":"product_order","product_pagination_limit":"2","desktop":{"items_per_row":"2"},"mobile":{"items_per_row":"1"},"hide_out_of_stock":"0"},"includes":{"show_search_box":"0","show_sort_by":"0","show_per_page":"0","show_category_dropdown":"0","show_currency_dropdown":"1","show_language_dropdown":"1","show_product_filters":"0","show_product_name":"1","show_product_price":"1","show_button_price":"1","show_product_image":"1","show_product_summary":"1","open_modal_on_image_click":"1","show_view_product_button":"1","show_add_to_cart_button":"1","show_min_max_order_quantity":"1","show_sale":"0","show_free_shipping":"0","show_new_product":"0","show_digital_download":"0","show_pwyw":"0","image_swap":"0","show_button_icons":"1","mobile":{"show_search_box":"0","show_sort_by":"0","show_per_page":"0","show_category_dropdown":"0","show_currency_dropdown":"1","show_language_dropdown":"1","show_product_filters":"0"}},"product_popup":{"show_product_name":true,"show_product_price":true,"show_button_price":true,"show_product_summary":true,"show_product_description":true,"show_product_image":false,"show_select_quantity":true,"show_image_thumbnails":false,"show_product_reviews":false,"show_product_sku":false,"show_product_categories":false,"show_social_sharing_icons":false,"show_related_products":false,"thumbnail_layout":"vertical_left","image_dimension_value":"fit","image_aspect_ratio":"portrait","variation_styling":"dropdown","show_min_max_order_quantity":true,"show_sale":false,"show_free_shipping":false,"show_new_product":false,"show_digital_download":false,"show_pwyw":false,"show_product_tabs":false,"image_zoom":false,"lightbox_gallery":"1","show_stock":false},"styles":{"align_content":"center","product_title":"#666666","product_price":"#666666","product_summary":"#666666","button_background":"#233642","button_color":"#ffffff","view_product_button_background":"#233642","view_product_button_color":"#ffffff","view_cart_button_background":"#233642","view_cart_button_color":"#ffffff","product_background":"#ffffff","modal_background":"#ffffff","button_font_weight":"normal","popup":{"colors":{"product_title":"#666666","product_price":"#666666","product_summary":"#666666","button_background":"#233642","button_color":"#ffffff","product_active_tab_background":"#f5f5f5"}}}}		</script>
	</div>

	<div class="sr-element" data-embed="basket">
		<script type="application/json" data-config="embed">
			{"publishable_key":"sr_live_pk_36fec20aa341629de1987702b121e402dc88","options":{"basket_style":"bubble","basket_position":"bottom-right"},"includes":{"show_pop_up_adding_item_to_cart":"1","show_image_thumbnails":"1","show_select_quantity":"1","show_overlay_when_open":"1","show_cart_count":"1","show_cart_total":"0"},"styles":{"basket_background":"#ffffff","basket_color":"#000000","basket_text_color":"#000000","basket_counter_background":"#000000","basket_counter_color":"#ffffff","cart_background":"#ffffff","cart_text_color":"#666666","cart_button_background":"#233642","cart_button_color":"#ffffff","cart_links_text_color":"#808b97","cart_border_color":"#eeeeee"}}		</script>
	</div>
	<script async src="https://cdn.shoprocket.io/loader.js"></script>

			<div class="store-bottom-text">
					</div>
	
	<script type="text/javascript">
		// light/dark
		var background = "#ffffff";
		var hexcolor = background.replace("#", "");
		var r = parseInt(hexcolor.substr(0, 2), 16);
		var g = parseInt(hexcolor.substr(2, 2), 16);
		var b = parseInt(hexcolor.substr(4, 2), 16);
		var yiq = ((r * 299) + (g * 587) + (b * 114)) / 1000;
		let isDark = (yiq >= 128) ? false : true;
		if (isDark) {
			let brandingLogo = document.querySelector('.sr-logo');
			if (brandingLogo) {
				brandingLogo.style.setProperty('filter', "brightness(0) invert(1)");
			}
		}

		let newsletterWrap = document.getElementById('newsletter-signup');
		if (newsletterWrap) {
			let emailEle = newsletterWrap.querySelector('input[name=hs_email]');
			newsletterWrap.querySelector('.hs-signup').addEventListener("click", function(e) {
				if (emailEle.value != "") {
					// hide all icons
					newsletterWrap.querySelector('.signup-error').classList.add('sr-hide');
					newsletterWrap.querySelector('.signup-success').classList.add('sr-hide');

					var subscribeBtn = newsletterWrap.querySelector('.hs-signup');
					var regex = /^([a-zA-Z0-9_.+-])+\@(([a-zA-Z0-9-])+\.)+([a-zA-Z0-9]{2,4})+$/;

					if (regex.test(emailEle.value)) {
						// hide button icons
						newsletterWrap.querySelector('span').classList.add('sr-hide');

						// show spin
						subscribeBtn.querySelector('.signup-loading').classList.remove('sr-hide');

						// reset
						document.getElementById('signup-error-message').innerText = "";

						var req = new XMLHttpRequest();
						req.addEventListener("load", function() {
							subscribeBtn.querySelector('.signup-loading').classList.add('sr-hide');
							response = JSON.parse(this.response);
							if (response.error) {
								subscribeBtn.querySelector('.signup-error').classList.remove('sr-hide');
								document.getElementById('signup-error-message').innerText = response.message;
							} else {
								subscribeBtn.querySelector('.signup-success').classList.remove('sr-hide');
							}
						});

						req.open("PUT", window.SR.storefront_xhr + 'customers', true);
						req.setRequestHeader('Content-Type', 'application/json');
						req.send(JSON.stringify({
							'marketing_subscribed': 1,
							'source': 'hosted store',
							'customer_email': emailEle.value,
							'csrf_test_name': document.querySelector('meta[name="csrf_token"]').content
						}));

						emailEle.value = "";
					}
					// invalid email
					else {
						setTimeout(function() {
							// hide all icons
							subscribeBtn.querySelector('i').classList.add('sr-hide');

							// hide text
							subscribeBtn.querySelector('.btn-text').classList.add('sr-hide');

							// show X icon
							subscribeBtn.querySelector('.fa-times-circle').classList.remove('sr-hide');
						}, 500);
					}
				}
			});
		}
	</script>

	<!-- Custom tracking code -->
	</body>

</html>
