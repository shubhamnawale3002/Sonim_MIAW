
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    
    <script type='text/javascript' src='https://service.force.com/embeddedservice/5.0/esw.min.js'></script>
     <script type='text/javascript'>
	function initEmbeddedMessaging() {
 	console.log('Came into the script before try ');
		try {
  			console.log('Came into the script');
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
  			console.log('Came into the script before try 2');
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://mtechmdm.my.site.com/ESWSonimChatSupport1725347723449/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
