
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = ''; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D0900000DaXno',
				'BMW_MIAWPOC',
				'https://bmw-ido0323-demo.my.site.com/ESWBMWMIAWPOC1686136459996',
				{
					scrt2URL: 'https://bmw-ido0323-demo.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://bmw-ido0323-demo.my.site.com/ESWBMWMIAWPOC1686136459996/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
