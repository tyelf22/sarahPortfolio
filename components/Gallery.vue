<template>
	<!-- galleryMain Content -->
	<div class="galleryMain">
		<!-- First Section -->
		<div class="container galleryContainers">
			<div class="row mb-5">
				<div class="col-12 align-self-center textSection">
					<h2>Interaction Design</h2>
					<div class="gradLine"></div>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/pgb3zr6N38Y`
							}
						}"
					>
						<img
							class="img-fluid"
							src="~/assets/images/gallery/tabletMag.jpg"
							alt="image of mac computer"
						/>
					</NuxtLink>

					<p class="text-center mt-3 px-1">
						Demo of interactive magazine concept for tablet
					</p>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<a
						class="toImageNuxtLink"
						href="/gallery/interactiveDemo/index.html"
					>
						<img
							class="img-fluid"
							src="~/assets/images/gallery/interactiveInfographicThumbnail.jpg"
							alt="image of mac computer"
						/>
					</a>
					<p class="text-center  mt-3 px-1">
						Interactive infographic made in Hype
					</p>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/0ggAxP-knMc`
							}
						}"
					>
						<img
							class="img-fluid "
							src="~/assets/images/gallery/fancySprinkles.jpg"
							alt="image of mac computer"
						/>
					</NuxtLink>
					<p class="text-center  mt-3 px-1">
						Demo of interactive magazine concept for Fancy Sprinkles
					</p>
				</div>
			</div>

			<!-- Motion Graphics -->
			<div class="row my-5">
				<div class="col-12 align-self-center textSection">
					<h2>Motion Graphics</h2>
					<div class="gradLine"></div>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/8Ehxe1HZWUE`
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/hypeGif.jpg"
							alt="image of mac computer"
						/>
					</NuxtLink>

					<p class="text-center px-1 mt-3">
						Original GIF created in Hype
					</p>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/8Ehxe1HZWUE`
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/hypeGif.jpg"
							alt="image of mac computer"
						/>
					</NuxtLink>
					<p class="text-center px-1 mt-3">
						Original GIF created in Hype
					</p>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/8Ehxe1HZWUE`
							}
						}"
					>
						<img
							class="img-fluid "
							src="@/assets/images/gallery/hypeGif.jpg"
							alt="image of mac computer"
						/>
					</NuxtLink>
					<p class="text-center px-1 mt-3">
						Original GIF created in Hype
					</p>
				</div>
			</div>
			<!-- Audio and Video -->
			<div class="row my-5">
				<div class="col-12 align-self-center textSection">
					<h2>Audio & Video</h2>
					<div class="gradLine"></div>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/QZ3lzG6Ly-4`
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/deeganOnFire.jpg"
							alt="image of mac computer"
						/>
					</NuxtLink>
					<p class="text-center px-1 mt-3">
						Video created in Photoshop - original footage &copy;
						Brian Deegan
					</p>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/QZ3lzG6Ly-4`
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/deeganOnFire.jpg"
							alt="image of mac computer"
						/>
					</NuxtLink>
					<p class="text-center px-1 mt-3">
						Video created in Photoshop - original footage &copy;
						Brian Deegan
					</p>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								vid: `https://www.youtube.com/embed/QZ3lzG6Ly-4`
							}
						}"
					>
						<img
							class="img-fluid "
							src="@/assets/images/gallery/deeganOnFire.jpg"
							alt="image of mac computer"
						/>
					</NuxtLink>
					<p class="text-center px-1 mt-3">
						Video created in Photoshop - original footage &copy;
						Brian Deegan
					</p>
				</div>
			</div>

			<!-- Illustrations -->
			<div class="row mt-5">
				<div class="col-12 align-self-center textSection">
					<h2>Illustrations</h2>
					<div class="gradLine"></div>
				</div>
				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								img: 'protegeThumbnail'
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/protegeThumbnail.jpg"
							alt="image of mac computer"
						/>
					</NuxtLink>
				</div>

				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								img: 'protegeThumbnail'
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/protegeThumbnail.jpg"
							alt="image of mac computer"
						/>
					</NuxtLink>
				</div>

				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						:to="{
							name: 'ImgBackground',
							params: {
								img: 'emilyThumbnail'
							}
						}"
					>
						<img
							class="img-fluid "
							src="@/assets/images/gallery/emilyThumbnail.jpg"
							alt="image of mac computer"
						/>
					</NuxtLink>
				</div>

				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						url="@/assets/images/gallery/summerThumbnailNew.jpg"
						:to="{
							name: 'ImgBackground',
							params: {
								img: 'summerThumbnailNew'
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/summerThumbnailNew.jpg"
							alt="image of mac computer"
						/>
					</NuxtLink>
				</div>

				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						url="@/assets/images/gallery/physicsThumbnail.jp"
						:to="{
							name: 'ImgBackground',
							params: {
								img: 'physicsThumbnail'
							}
						}"
					>
						<img
							class="img-fluid"
							src="@/assets/images/gallery/physicsThumbnail.jpg"
							alt="image of mac computer"
						/>
					</NuxtLink>
				</div>

				<div
					class="col-12 px-0 px-md-2 px-lg-3 col-md-4 my-4 align-self-start"
				>
					<NuxtLink
						class="toImageNuxtLink"
						url="@/assets/images/gallery/mightyFicusThumbnail.jpg"
						:to="{
							name: 'ImgBackground',
							params: {
								img: 'mightyFicusThumbnail'
							}
						}"
					>
						<img
							class="img-fluid "
							src="@/assets/images/gallery/mightyFicusThumbnail.jpg"
							alt="image of mac computer"
						/>
					</NuxtLink>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
import GradButton from "@/components/GradButton";
export default {
	components: {
		GradButton
	},
	data() {
		return {
			active: "digital"
		};
	}
};
</script>

<style lang="scss" scoped>
.galleryMain {
	color: black;

	.galleryContainers {
		padding-top: 100px;
		padding-bottom: 100px;

		.textSection {
			padding-left: 50px;
			padding-right: 50px;

			h4 {
				font-size: 14px;
				letter-spacing: $tracking250;
			}

			h2 {
				font-size: 50px;
				font-family: "Made";
				color: $header;
			}
		}

		p {
			font-size: 18px;
			color: $bodyGray;
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
	.galleryMain {
		.galleryContainers {
			.textSection {
				padding-left: 15px;
				padding-right: 15px;

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
</style>
