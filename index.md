<!DOCTYPE html>
<html>
    <body>
        <script type='text/javascript'>
            function initEmbeddedMessaging() {
                try {
                    embeddedservice_bootstrap.settings.language = 'es'; // For example, enter 'en' or 'en-US'
        
                    embeddedservice_bootstrap.init(
                        '00D7X000000TaGc',
                        'Alemana_Go_Miaw2',
                        'https://orgalemana--casdev6.sandbox.my.site.com/ESWAlemanaGoMiaw21695253769422',
                        {
                            scrt2URL: 'https://orgalemana--casdev6.sandbox.my.salesforce-scrt.com'
                        }
                    );
                } catch (err) {
                    console.error('Error loading Embedded Messaging: ', err);
                }
            };
        </script>
        <script type='text/javascript' src='https://orgalemana--casdev6.sandbox.my.site.com/ESWAlemanaGoMiaw21695253769422/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
        
    </body>
</html>
    

