<template>
	<!-- brandishApp Content -->
	<div class="brandishApp">
		<div @click="$router.go(-1)" class="close">
			<img
				id="closeImg"
				src="@/assets/images/closeHover.png"
				src2="@/assets/images/close.png"
			/>
		</div>
		<!-- First Section -->
		<div class="container projectContainers" id="firstProjContainer">
			<div class="row">
				<div class="col-12 align-self-center textSection">
					<h4>Utah Valley University</h4>
					<h2>Brandish App</h2>
					<div class="gradLine"></div>
					<p>
						November 2020
					</p>
				</div>
			</div>
		</div>
		<!-- Second Section -->
		<div class="container-fluid infoColor projectContainers">
			<div class="row">
				<div class="container">
					<div class="row ">
						<div
							class="col-12 col-md-5 col-lg-6 order-md-2 align-self-center"
						>
							<img
								class="img-fluid"
								id="macImg"
								src="@/assets/images/digital/brandishApp.png"
								alt="image of mac computer"
							/>
						</div>
						<div
							class="col-12 col-md-7 col-lg-6 order-md-1 align-self-center  textSection"
						>
							<h2>The Problem</h2>
							<p>
								Lorem ipsum dolor sit amet, consectetur
								adipiscing elit. Nullam dapibus convallis sapien
								sed egestas. Nunc suscipit sem lorem, non
								pretium risus rutrum ut. Mauris sagittis urna
							</p>

							<h4 class="purpHeader">Deliverables</h4>
							<p class="highFidText">High-fidelity prototype</p>
							<GradButton
								title="Go To XD Adobe.com"
								url="https://xd.adobe.com/view/729e9ab2-12f3-4c6f-9d05-5ce0775a0fbd-27cd/"
							/>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- Third Section -->
		<div class="container-fluid projectContainers">
			<div class="row justify-content-md-center">
				<div class="container">
					<div class="row justify-content-md-center">
						<div
							class="col-12 col-md-10 align-self-center px-4 px-md-0 textSection"
						>
							<h2 class="text-center ">The Solution</h2>
							<h4 class="text-center subtitle firstHeader">
								Research
							</h4>

							<p class="text-left">
								Lorem ipsum dolor sit amet, consectetur
								adipiscing elit. Nullam dapibus convallis sapien
								sed egestas. Nunc suscipit sem lorem, non
								pretium risus rutrum ut. Mauris sagittis urna
								elit, efficitur convallis nisi feugiat quis. Ut
								lacus est, egestas vel feugiat in, vehicula quis
								tortor. Cras pretium odio nisl, eget dignissim
								nunc commodo et.
								<br />

								Aliquam hendrerit vitae tortor id iaculis.
								Vestibulum varius quam eros, sit amet mattis
								nulla varius vel. Maecenas feugiat mi quis
								mattis ultricies. Morbi vitae lectus in erat
								blandit egestas. Vestibulum ante ipsum primis in
								faucibus orci luctus et ultrices posuere cubilia
								curae; Mauris ultricies blandit metus, et cursus
								urna congue ut. Mauris mollis tortor eget nisl
								scelerisque sagittis. Etiam nisl orci, malesuada
								et aliquet vel, congue sit amet ex. Curabitur
								tincidunt lacinia ligula, eu pellentesque lectus
								vestibulum vitae. Sed eu mauris eu sem viverra
								aliquet. Aliquam erat volutpat. Sed lacinia
								massa ornare rhoncus facilisis.
							</p>

							<h4 class="text-center subtitle">Ux Framework</h4>
							<br />

							<p>
								Lorem ipsum dolor sit amet, consectetur
								adipiscing elit. Nullam dapibus convallis sapien
								sed egestas. Nunc suscipit sem lorem, non
								pretium risus rutrum ut. Mauris sagittis urna
								elit.
								<br />

								Aliquam hendrerit vitae tortor id iaculis.
								Vestibulum varius quam eros, sit amet mattis
								nulla varius vel. Maecenas feugiat mi quis
								mattis ultricies. Morbi vitae lectus in erat
								blandit egestas. Vestibulum ante ipsum primis in
								faucibus orci luctus et ultrices posuere cubilia
								curae;
							</p>

							<h4 class="text-center subtitle">Ideation</h4>
							<br />

							<p>
								Lorem ipsum dolor sit amet, consectetur
								adipiscing elit. Nullam dapibus convallis sapien
								sed egestas. Nunc suscipit sem lorem, non
								pretium risus rutrum ut. Mauris sagittis urna
								elit.
								<br />

								Aliquam hendrerit vitae tortor id iaculis.
								Vestibulum varius quam eros, sit amet mattis
								nulla varius vel. Maecenas feugiat mi quis
								mattis ultricies. Morbi vitae lectus in erat
								blandit egestas. Vestibulum ante ipsum primis in
								faucibus orci luctus et ultrices posuere cubilia
								curae;
							</p>

							<h4 class="text-center subtitle">Ui Design</h4>
							<br />

							<p>
								Lorem ipsum dolor sit amet, consectetur
								adipiscing elit. Nullam dapibus convallis sapien
								sed egestas. Nunc suscipit sem lorem, non
								pretium risus rutrum ut. Mauris sagittis urna
								elit.
								<br />

								Aliquam hendrerit vitae tortor id iaculis.
								Vestibulum varius quam eros, sit amet mattis
								nulla varius vel. Maecenas feugiat mi quis
								mattis ultricies. Morbi vitae lectus in erat
								blandit egestas. Vestibulum ante ipsum primis in
								faucibus orci luctus et ultrices posuere cubilia
								curae;
							</p>

							<h4 class="text-center subtitle">Iteration</h4>
							<br />

							<p>
								Lorem ipsum dolor sit amet, consectetur
								adipiscing elit. Nullam dapibus convallis sapien
								sed egestas. Nunc suscipit sem lorem, non
								pretium risus rutrum ut. Mauris sagittis urna
								elit.
								<br />
								<br />
								Aliquam hendrerit vitae tortor id iaculis.
								Vestibulum varius quam eros, sit amet mattis
								nulla varius vel. Maecenas feugiat mi quis
								mattis ultricies. Morbi vitae lectus in erat
								blandit egestas. Vestibulum ante ipsum primis in
								faucibus orci luctus et ultrices posuere cubilia
								curae;
							</p>

							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/digital/first.jpg"
								alt="image of mobile phone app design"
							/>
							<figcaption class="text-center mt-3">
								First Iteration
							</figcaption>

							<img
								class="img-fluid px-0 mt-5"
								src="@/assets/images/digital/second.jpg"
								alt="image of mobile phone app design"
							/>
							<figcaption class="text-center mt-3">
								Second Iteration
							</figcaption>

							<h4 class="text-center subtitle">
								Problem Solving
							</h4>
							<br />

							<p>
								Lorem ipsum dolor sit amet, consectetur
								adipiscing elit. Nullam dapibus convallis sapien
								sed egestas. Nunc suscipit sem lorem, non
								pretium risus rutrum ut. Mauris sagittis urna
								elit.
								<br />
								<br />
								Aliquam hendrerit vitae tortor id iaculis.
								Vestibulum varius quam eros, sit amet mattis
								nulla varius vel. Maecenas feugiat mi quis
								mattis ultricies. Morbi vitae lectus in erat
								blandit egestas. Vestibulum ante ipsum primis in
								faucibus orci luctus et ultrices posuere cubilia
								curae;
							</p>

							<div class="embed-responsive embed-responsive-4by3">
								<iframe
									class="embed-responsive-item px-0 mt-5"
									src="https://www.youtube.com/embed/TdsgREfA6BQ"
									title="YouTube video player"
									frameborder="0"
									allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture allowfullscreen"
								>
								</iframe>
							</div>
							<figcaption class="text-center mt-3">
								Second Iteration
							</figcaption>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="container-fluid projectContainers infoColor">
			<div class="row justify-content-md-center">
				<div class="container">
					<div
						class="col-12 align-self-center px-4 px-md-0 textSection"
					>
						<h4 class="text-center subtitle firstHeader">
							Lessons Learned
						</h4>

						<p class="text-left">
							Lorem ipsum dolor sit amet, consectetur adipiscing
							elit. Nullam dapibus convallis sapien sed egestas.
							Nunc suscipit sem lorem, non pretium risus rutrum
							ut. Mauris sagittis urna elit, efficitur convallis
							nisi feugiat quis. Ut lacus est, egestas vel feugiat
							in, vehicula quis tortor. Cras pretium odio nisl,
							eget dignissim nunc commodo et.
							<br />
							<br />

							Aliquam hendrerit vitae tortor id iaculis.
							Vestibulum varius quam eros, sit amet mattis nulla
							varius vel. Maecenas feugiat mi quis mattis
							ultricies. Morbi vitae lectus in erat blandit
							egestas. Vestibulum ante ipsum primis in faucibus
							orci luctus et ultrices posuere cubilia curae;
							Mauris ultricies blandit metus, et cursus urna
							congue ut. Mauris mollis tortor eget nisl
							scelerisque sagittis. Etiam nisl orci, malesuada et
							aliquet vel, congue sit amet ex. Curabitur tincidunt
							lacinia ligula, eu pellentesque lectus vestibulum
							vitae. Sed eu mauris eu sem viverra aliquet. Aliquam
							erat volutpat. Sed lacinia massa ornare rhoncus
							facilisis.
						</p>

						<h4 class="purpHeader text-center">Deliverables</h4>
						<p class="text-center highFidText">
							High-fidelity prototype
						</p>
						<GradButton
							class="text-center"
							title="Go To XD Adobe.com"
							url="https://xd.adobe.com/view/729e9ab2-12f3-4c6f-9d05-5ce0775a0fbd-27cd/"
						/>
					</div>
				</div>
			</div>
		</div>
		<NextNav
			:class="{
				noNav: scrollPosition < 100,
				showNav: scrollPosition > 100
			}"
			next=""
			prev="/userResearch"
		/>
	</div>
</template>

<script>
import GradButton from "@/components/GradButton";
import NextNav from "@/components/NextNav";

export default {
	components: {
		GradButton,
		NextNav
	},

	data() {
		return {
			scrollPosition: null
		};
	},

	mounted() {
		window.addEventListener("scroll", this.updateScroll);
	},
	methods: {
		updateScroll() {
			this.scrollPosition = window.scrollY;
		}
	},
	destroy() {
		window.removeEventListener("scroll", this.updateScroll);
	}
};
</script>

<style lang="scss" scoped>
.brandishApp {
	color: black;

	.noNav {
	}

	.showNav {
		position: fixed;
		bottom: 0;
		opacity: 0.99;

		animation: fadeIn 1s;
		-webkit-animation: fadeIn 1s;
		-moz-animation: fadeIn 1s;
		-o-animation: fadeIn 1s;
		-ms-animation: fadeIn 1s;
	}

	@keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	@-moz-keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	@-webkit-keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	@-o-keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	@-ms-keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	.close {
		position: absolute;
		right: 20px;
		top: 20px;
		height: 32px;
		cursor: pointer;

		#closeImg {
			content: url("@/assets/images/closeHover.png");
			content: url("@/assets/images/close.png");
			width: 45px;

			&:hover {
				content: url("@/assets/images/closeHover.png");
			}
		}
	}

	#firstProjContainer {
		padding-bottom: 200px;
	}

	.projectContainers {
		padding-top: 100px;
		padding-bottom: 100px;

		#macImg {
			margin-top: -250px;
			margin-bottom: 100px;
		}

		.textSection {
			h4 {
				font-size: 14px;
				letter-spacing: $tracking250;
			}
			.subtitle {
				text-transform: uppercase;
				margin: 120px 0 30px 0;
				font-size: 20px;
			}

			.firstHeader {
				margin: 40px 0;
			}

			h2 {
				font-size: 50px;
				font-family: "Made";
				color: $header;
			}

			p {
				font-size: 18px;
			}

			figcaption {
				color: $bodyGray;
			}

			.purpHeader {
				font-size: 18px;
				background-image: linear-gradient(
					to right,
					$gradDark,
					$gradLight
				);
				background-clip: text;
				-webkit-text-fill-color: transparent;
				-moz-text-fill-color: transparent;
				text-transform: uppercase;
				margin-top: 25px;
			}

			.highFidText {
				margin-bottom: -25px;
			}
		}

		.gradLine {
			height: 3px;
			width: 80px;
			margin: 20px 0;
			background-image: linear-gradient(to right, $gradDark, $gradLight);
		}
	}

	.infoColor {
		background-image: linear-gradient(
			to right,
			$bgLightPurple,
			$bgDarkPurple
		);
	}
}

@media only screen and (min-width: 768px) {
	.brandishApp {
		.projectContainers {
			#macImg {
				margin-top: -400px;
				margin-bottom: 0;
			}

			.textSection {
				h4 {
					font-size: 16px;
					letter-spacing: $tracking250;
				}

				h2 {
					font-size: 60px;
					font-family: "Made";
					color: $header;
				}
			}
		}
	}
}

@media only screen and (min-width: 992px) {
	.brandishApp {
		.projectContainers {
			#macImg {
				margin-top: -500px;
				margin-bottom: 100px;
			}
		}
	}
}
</style>
