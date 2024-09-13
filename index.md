<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D61000000ZHu3',
				'Sonim_Chat_Support',
				'https://mtechmdm.my.site.com/ESWSonimChatSupport1725347723449',
				{
					scrt2URL: 'https://mtechmdm.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://mtechmdm.my.site.com/ESWSonimChatSupport1725347723449/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
