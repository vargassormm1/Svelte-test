<script>
	export const prerender = true;
	import { Lightbox } from 'svelte-lightbox';
</script>

<div class="photos">
	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/1_nHS1JnLFrL.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468523301"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/2_T6z6xsyDh.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468522903"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/3_eswNU4Ag4.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468523275"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/4_w_OaOV_1j.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468523515"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/5_t6xeYRids.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468523085"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/6_4ad6tA6vP.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468523418"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/7_cr8ezgZnV.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468522857"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/8_9wg7h6-Tt.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468521603"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/9_kZXwEbf5v.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468521774"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/10_pvXoiuFyrk.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468522121"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/11_6g7FlB0OTc.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468521696"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/12_ECWIWxCYb.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468522111"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/13_5rG0GG5Jk.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468521470"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/14_kzve6MLR9.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468521762"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/15_OYqLAmOYW.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468521669"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/16_Vpiqm8cNd.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468521939"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/17_XNKUfUuZJb.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468522559"
			alt=""
		/>
	</Lightbox>

	<Lightbox showCloseButton="false">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Portraits/18_gqyu9rGFY.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672468522631"
			alt=""
		/>
	</Lightbox>
</div>

<style>
	.photos {
		display: grid;
		grid-template-columns: repeat(6, 1fr);
		gap: 10px;
		row-gap: 1rem;
		column-gap: 1rem;
	}
	.photos img {
		width: 100%;
		height: auto;
		display: block;
		margin: 0 1px 10px 1px;
		cursor: pointer;
	}

	/* Media Query */
	@media (max-width: 500px) {
		.photos {
			display: grid;
			grid-template-columns: repeat(2, 1fr);
			gap: 10px;
			row-gap: 3rem;
			column-gap: 3rem;
		}
		.photos {
			height: 100%;
			padding: 0 1rem;
			column-count: 2;
		}
		.photos img {
			margin: 1px 1px 5px 1px;
		}
	}
</style>
