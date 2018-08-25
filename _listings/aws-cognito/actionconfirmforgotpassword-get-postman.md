{
  "info": {
    "name": "AWS Cognito API Confirm Forgot Password",
    "_postman_id": "7969e671-d976-46fe-a127-2366ac370c0f",
    "description": "Allows a user to enter a code provided when they reset their password to update\n            their password.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Attributes",
      "item": [
        {
          "id": "09140f71-cd4e-4975-9988-6b31d220786d",
          "name": "addCustomAttributes",
          "request": {
            "url": "http://example.com/api/?Action=AddCustomAttributes?CustomAttributes=CustomAttributes&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds additional user attributes to the user pool schema."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1fe85fa8-1d76-4261-bdee-ace417193f77"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "8517a765-ab4f-469e-ab68-a2c0e64bc9ee",
          "name": "adminAddUserToGroup",
          "request": {
            "url": "http://example.com/api/?Action=AdminAddUserToGroup?GroupName=GroupName&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the specified user to the specified group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d3c9a33b-f1c4-4490-ae02-e0784d214d98"
            }
          ]
        },
        {
          "id": "2c6d3288-2a6a-4cd9-bc51-c9a85487d0a0",
          "name": "adminCreateUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminCreateUser?DesiredDeliveryMediums=DesiredDeliveryMediums&ForceAliasCreation=ForceAliasCreation&MessageAction=MessageAction&TemporaryPassword=TemporaryPassword&UserAttributes=UserAttributes&Username=Username&UserPoolId=UserPoolId&ValidationData=ValidationData",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new user in the specified user pool and sends a welcome message via email\n            or phone (SMS)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "649911ae-6ed0-4fad-9db8-8fde33a77862"
            }
          ]
        },
        {
          "id": "f124e4dc-b84b-4f46-acb7-9fd548e6ad6f",
          "name": "adminDeleteUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminDeleteUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a user as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "25934e99-f226-47e5-a1f0-5318c2732b18"
            }
          ]
        },
        {
          "id": "99f57291-744c-4dc8-a027-3700696fd452",
          "name": "adminDeleteUserAttributes",
          "request": {
            "url": "http://example.com/api/?Action=AdminDeleteUserAttributes?UserAttributeNames=UserAttributeNames&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the user attributes in a user pool as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0214983-483c-4573-ae48-ffbb9ba5d1b8"
            }
          ]
        },
        {
          "id": "c7ed4b64-8ecb-44eb-8d90-dfd9b808eb6c",
          "name": "adminDisableUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminDisableUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables the specified user as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "00675222-7548-408d-b5fe-9e9277b49798"
            }
          ]
        },
        {
          "id": "597a9a84-1ccd-45ea-85ab-32bfb6df449d",
          "name": "adminEnableUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminEnableUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables the specified user as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab9a0f3e-63fc-4842-a681-d014adad2e0d"
            }
          ]
        },
        {
          "id": "855af4d6-34e1-4ed1-93eb-d338195f84f9",
          "name": "adminGetUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminGetUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the specified user by user name in a user pool as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7049a024-8cc3-41dd-81af-11a55a74c836"
            }
          ]
        },
        {
          "id": "1d6f70f4-bfaa-4f8a-ab09-79f9638dfa3f",
          "name": "adminListGroupsForUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminListGroupsForUser?Limit=Limit&NextToken=NextToken&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the groups that the user belongs to."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c2fe7560-9cf9-442b-873b-72baa422ec32"
            }
          ]
        },
        {
          "id": "f92fd4c8-c973-49f3-9602-8803babf2478",
          "name": "adminRemoveUserFromGroup",
          "request": {
            "url": "http://example.com/api/?Action=AdminRemoveUserFromGroup?GroupName=GroupName&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified user from the specified group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f64198fe-bb41-446d-ab5f-10baf45bb87a"
            }
          ]
        },
        {
          "id": "2a260983-6464-4d1c-a131-365d36f95321",
          "name": "adminResetUserPassword",
          "request": {
            "url": "http://example.com/api/?Action=AdminResetUserPassword?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets the specified user's password in a user pool as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e60b7f3-2bb7-4a78-a6b6-08d129c45946"
            }
          ]
        },
        {
          "id": "16b9f708-afb5-4814-ae9f-cac6038f35e4",
          "name": "adminSetUserSettings",
          "request": {
            "url": "http://example.com/api/?Action=AdminSetUserSettings?MFAOptions=MFAOptions&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets all the user settings for a specified user name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59f86f27-bdf4-4348-8435-1952cc4df06e"
            }
          ]
        },
        {
          "id": "b7a4f64e-7411-481c-aeb1-4ec9902ccdf4",
          "name": "adminUpdateDeviceStatus",
          "request": {
            "url": "http://example.com/api/?Action=AdminUpdateDeviceStatus?DeviceKey=DeviceKey&DeviceRememberedStatus=DeviceRememberedStatus&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the device status as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b100924c-c7d1-4a54-a2a3-c9d4c550bd97"
            }
          ]
        },
        {
          "id": "0fc2d4dd-0681-4fae-ae8e-439841193d29",
          "name": "adminUpdateUserAttributes",
          "request": {
            "url": "http://example.com/api/?Action=AdminUpdateUserAttributes?UserAttributes=UserAttributes&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the specified user's attributes, including developer attributes, as an\n            administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae645d2f-dd4c-49bc-9bf5-fbc325eb39b8"
            }
          ]
        },
        {
          "id": "b2b2ae54-3866-42d1-a796-bc6e688f80d1",
          "name": "adminUserGlobalSignOut",
          "request": {
            "url": "http://example.com/api/?Action=AdminUserGlobalSignOut?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Signs out users from all devices, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d3cf253a-6ab1-4e9b-bad8-a770801228e8"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Up",
      "item": [
        {
          "id": "0b3aaef8-7d59-4706-b090-087a35619573",
          "name": "adminConfirmSignUp",
          "request": {
            "url": "http://example.com/api/?Action=AdminConfirmSignUp?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Confirms user registration as an admin without using a confirmation code."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f07f7810-7865-48e2-b734-149d0e5896cc"
            }
          ]
        }
      ]
    },
    {
      "name": "Devices",
      "item": [
        {
          "id": "23a2bbd9-6f7f-46da-b2c8-4bd62ace3315",
          "name": "adminForgetDevice",
          "request": {
            "url": "http://example.com/api/?Action=AdminForgetDevice?DeviceKey=DeviceKey&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Forgets the device, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f8a5cfa-04a1-491c-b094-607144b3bc3e"
            }
          ]
        },
        {
          "id": "ad7137a5-c39f-43a1-abb4-26b03cf81ee3",
          "name": "confirmDevice",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmDevice?AccessToken=AccessToken&DeviceKey=DeviceKey&DeviceName=DeviceName&DeviceSecretVerifierConfig=DeviceSecretVerifierConfig",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Confirms tracking of the device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7cef1b61-b53a-413a-8968-87e61e1ae251"
            }
          ]
        }
      ]
    },
    {
      "name": "http://laneworks.net/api-stack/pull/pull-amazon-cognito-sync.php",
      "item": [
        {
          "id": "d383a820-6a4b-451e-9faf-7473731e2285",
          "name": "adminGetDevice",
          "request": {
            "url": "http://example.com/api/?Action=AdminGetDevice?DeviceKey=DeviceKey&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the device, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f5a24f6-cb4b-4963-b3f7-3052d4bb387f"
            }
          ]
        },
        {
          "id": "1676e3b6-540a-43ed-95fb-641460ac98d1",
          "name": "adminListDevices",
          "request": {
            "url": "http://example.com/api/?Action=AdminListDevices?Limit=Limit&PaginationToken=PaginationToken&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists devices, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b89df070-ba8b-4fc8-b1f4-4b455030076b"
            }
          ]
        }
      ]
    },
    {
      "name": "Authnetication",
      "item": [
        {
          "id": "bab8f0f3-d1fc-422e-bd0b-4628af60cde2",
          "name": "adminInitiateAuth",
          "request": {
            "url": "http://example.com/api/?Action=AdminInitiateAuth?AuthFlow=AuthFlow&AuthParameters=AuthParameters&ClientId=ClientId&ClientMetadata=ClientMetadata&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates the authentication flow, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d97b3077-9285-47dd-8084-0aa62e392f47"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication Challenge",
      "item": [
        {
          "id": "7d15fc63-54f7-4796-b710-465292c1a820",
          "name": "adminRespondToAuthChallenge",
          "request": {
            "url": "http://example.com/api/?Action=AdminRespondToAuthChallenge?ChallengeName=ChallengeName&ChallengeResponses=ChallengeResponses&ClientId=ClientId&Session=Session&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Responds to an authentication challenge, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b57d36a7-71c9-48dc-aafc-73546688a789"
            }
          ]
        }
      ]
    },
    {
      "name": "Password",
      "item": [
        {
          "id": "114e3644-4558-4915-aa4d-954589ddf19c",
          "name": "changePassword",
          "request": {
            "url": "http://example.com/api/?Action=ChangePassword?AccessToken=AccessToken&PreviousPassword=PreviousPassword&ProposedPassword=ProposedPassword",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Changes the password for a specified user in a user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "47d584bf-6b4f-47b4-8cd4-1a7d98d89b9b"
            }
          ]
        }
      ]
    },
    {
      "name": "Passwords",
      "item": [
        {
          "id": "d969d7ab-a29b-4e75-8055-2191ff626416",
          "name": "confirmForgotPassword",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmForgotPassword?ClientId=ClientId&ConfirmationCode=ConfirmationCode&Password=Password&SecretHash=SecretHash&Username=Username",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows a user to enter a code provided when they reset their password to update\n            their password."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d61b134e-d91a-431c-b186-5be76d404368"
            }
          ]
        }
      ]
    }
  ]
}