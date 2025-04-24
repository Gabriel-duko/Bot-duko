<html>
	<body>
		<script type='text/javascript'>
		function initEmbeddedMessaging() {
		try {
		embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

		embeddedservice_bootstrap.init(
		'00Dak00000QGSe6',
		'Web_Chat',
		'https://creative-impala-fzbtn3-dev-ed.trailblaze.my.site.com/ESWWebChat1745434042807',
		{
			scrt2URL: 'https://creative-impala-fzbtn3-dev-ed.trailblaze.my.salesforce-scrt.com'
		}
		);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
		};
		</script>
		<script type='text/javascript' src='https://creative-impala-fzbtn3-dev-ed.trailblaze.my.site.com/ESWWebChat1745434042807/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
	</body>
</html>
