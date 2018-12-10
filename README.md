# facebook-kit-phone-auth
Run this project step by step 

step 1, git clone (project url)

step 2, In Login.html file add your app info

appId:"{{FACEBOOK_APP_ID}}", 
state:"{{csrf}}", 
version:"{{ACCOUNT_KIT_API_VERSION}}",
fbAppEventsEnabled:true,
redirect:"{{REDIRECT_URL}}"

step 3, In server.js file add your app info

const account_kit_api_version = '{{ACCOUNT_KIT_API_VERSION}}';
const app_id = '{{FACEBOOK_APP_ID}}';
const app_secret = '{{ACCOUNT_KIT_APP_SECRET}}';
const me_endpoint_base_url = 'https://graph.accountkit.com/{{ACCOUNT_KIT_API_VERSION}}/me';
const token_exchange_base_url = 'https://graph.accountkit.com/{{ACCOUNT_KIT_API_VERSION}}/access_token'; 

step 4, npm install
step 5, npm start
