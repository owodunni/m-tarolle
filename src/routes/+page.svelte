<script lang="ts">
	import { type PageSeoMetaData, PageSeo } from '@owodunni/bricks-ui';

	const seoMeta: PageSeoMetaData = {
		name: 'hello',
		description: '',
		url: 'https://hello.se',
		ldImage: {
			name: '',
			url: 'https://hello.se',
			width: 600,
			height: 315
		},
		ogImage: {
			name: '',
			url: 'https://hello.se',
			width: 1920,
			height: 1080
		},
		organization: {
			name: '',
			url: 'https://hello.se',
			email: 'test@email.se',
			legalName: ''
		}
	};
</script>

<PageSeo seo={seoMeta} />

<h1>Mätarolle.se</h1>
