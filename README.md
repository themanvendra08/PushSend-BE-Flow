# Getting Started With PushSend AI

## Step 1: Seeding the data to database -
1. Roles - `{{BASE_URL}}/user-trigger/create-role`
2. Categories & Sub-Categories - `{{BASE_URL}}/audience-store-trigger/category-dump`
3. Subscription Plans - `{{BASE_URL}}/payment-trigger/seed-plans`

## Step 2: On Bording - 
1. SignUp  |  POST  |  `{{BASE_URL}}/user-trigger/signup`
2. Verify Email  | POST  |  `{{BASE_URL}}/user-trigger/verify-email?confirmation_token=<your-confirmation-token>&email=<your-email>`
3. Create Store  |  POST | `{{BASE_URL}}/store-trigger/create-store`
4. Store-Details | POST | `{{BASE_URL}}/audience-store-trigger/store-details`
5. Promotion-Details | POST | `{{BASE_URL}}/audience-store-trigger/promotional-details`

## 
