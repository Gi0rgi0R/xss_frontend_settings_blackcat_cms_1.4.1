# XSS in BlackCat CMS Frontend Settings

Software link: BlacCat CMS [https://blackcat-cms.org/]

Version: 1.4.1

@author: Jorge Riopedre

Description: BlackCat CMS 1.4.1 is affected by a Cross-site scripting (XSS) vulnerability in upload/backend/settings/index.php that allows remote attackers to inject arbitrary web script or HTML via the 'Website header' or 'Website footer' parameter.

# POC

1. Go to Settings - Frontend settings and change the 'Website header' or 'Website footer' parameters with the payload and Save.

![imagen](https://github.com/Gi0rgi0R/xss_frontend_settings_blackcat_cms_1.4.1/assets/145793179/9987fb23-98e3-4b93-8e38-e4610c019590)

2. Select any of the pages in the left menu

![imagen](https://github.com/Gi0rgi0R/xss_frontend_settings_blackcat_cms_1.4.1/assets/145793179/19e43c68-7568-4254-95d0-6111ea5b8c9c)

3. Click the "View page" option

![imagen](https://github.com/Gi0rgi0R/xss_frontend_settings_blackcat_cms_1.4.1/assets/145793179/4804ce1f-9081-447a-98bd-a327ccfd5d8d)

![imagen](https://github.com/Gi0rgi0R/xss_frontend_settings_blackcat_cms_1.4.1/assets/145793179/36d96d67-04d2-4d13-b0e8-b4657b63bab4)




