{
  "info": {
    "name": "AWS Cognito API Delete User",
    "_postman_id": "1d50dd1e-093c-4a73-8486-e161dcf85b52",
    "description": "Allows a user to delete one's self.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Attributes",
      "item": [
        {
          "id": "a3f36dfc-f628-4ef9-8ea5-0c28b9b12934",
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
              "id": "89c1b786-9639-4fed-ba84-13aa11d1040f"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "bfd9045d-c997-4107-871a-9407a387915b",
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
              "id": "21a88452-538a-4e4d-b79d-18869073cfe9"
            }
          ]
        },
        {
          "id": "199c67bf-d61d-4c47-b0a1-188cfba9aa6c",
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
              "id": "291832da-1db7-4ba1-9c56-1c59ea7befd0"
            }
          ]
        },
        {
          "id": "0a1cdeea-428f-4479-a89c-0073b7095c84",
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
              "id": "ff7f6fab-c14f-45d0-b1b1-416b3146ca53"
            }
          ]
        },
        {
          "id": "d7bfef35-4760-4009-9534-4405ed67ae6c",
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
              "id": "4ce94b0d-0c5e-4eb9-b1e0-d6f1a66ba05f"
            }
          ]
        },
        {
          "id": "9a84fbaf-c8db-4a94-963b-56d461b078f5",
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
              "id": "c6c3e07e-fae7-468c-9433-3f30f2b148dd"
            }
          ]
        },
        {
          "id": "694c3141-6ab4-46de-bb1d-8fad531263ad",
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
              "id": "18b35919-cd24-42ba-86d8-364908b762c7"
            }
          ]
        },
        {
          "id": "15019c59-c901-4657-a4d1-33d38569c5a9",
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
              "id": "923de45a-6102-41cd-85eb-d6ff17a7d0ef"
            }
          ]
        },
        {
          "id": "79aac1ab-ff16-4fb9-a5a6-fcd13ac8024f",
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
              "id": "2bb9dad9-ba13-438f-9a8d-133d1aaabc24"
            }
          ]
        },
        {
          "id": "712dac3f-5867-4618-95a7-78c3cd9b1a03",
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
              "id": "2770e83f-e76e-436c-91ab-e2a64bbe8e39"
            }
          ]
        },
        {
          "id": "78b491c1-84e5-42df-a4d5-2ace1b67feda",
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
              "id": "9a4ad77c-120a-4caa-bdb3-55cfc83e3604"
            }
          ]
        },
        {
          "id": "6b3eec7f-eabe-454e-9ea0-9ca98b8335da",
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
              "id": "f2cdf985-0065-45c0-9912-a49c2a173ef6"
            }
          ]
        },
        {
          "id": "5d9079c2-6fcc-4dfb-83ee-a12ca677e8c1",
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
              "id": "062d56d0-cd74-45cf-9f77-8d8be178c474"
            }
          ]
        },
        {
          "id": "4cb44951-39f5-4855-be66-91b17af2f786",
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
              "id": "4cea4ac4-0583-49c2-b8f2-bfdc1d2961e1"
            }
          ]
        },
        {
          "id": "e452dc66-2fbb-44c6-9226-add481e14b91",
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
              "id": "624802c9-0432-433c-a256-12558b61dcac"
            }
          ]
        },
        {
          "id": "bf535fd1-6df8-461b-be35-fdd1a52563ab",
          "name": "createUserImportJob",
          "request": {
            "url": "http://example.com/api/?Action=CreateUserImportJob?CloudWatchLogsRoleArn=CloudWatchLogsRoleArn&JobName=JobName&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates the user import job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "665380bf-6b3b-42c7-8933-5fdc631ec5d6"
            }
          ]
        },
        {
          "id": "ec146a28-4851-4eb4-b691-420f7c21a080",
          "name": "createUserPool",
          "request": {
            "url": "http://example.com/api/?Action=CreateUserPool?AdminCreateUserConfig=AdminCreateUserConfig&AliasAttributes=AliasAttributes&AutoVerifiedAttributes=AutoVerifiedAttributes&DeviceConfiguration=DeviceConfiguration&EmailConfiguration=EmailConfiguration&EmailVerificationMessage=EmailVerificationMessage&EmailVerificationSubject=EmailVerificationSubject&LambdaConfig=LambdaConfig&MfaConfiguration=MfaConfiguration&Policies=Policies&PoolName=PoolName&Schema=Schema&SmsAuthenticationMessage=SmsAuthenticationMessage&SmsConfiguration=SmsConfiguration&SmsVerificationMessage=SmsVerificationMessage&UserPoolTags=UserPoolTags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new Amazon Cognito user pool and sets the password policy for the\n            pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2201b861-418b-41cc-98a9-3e14e0534e0b"
            }
          ]
        },
        {
          "id": "43bb9ffe-cb2e-4588-9976-80ddb615d0d8",
          "name": "createUserPoolClient",
          "request": {
            "url": "http://example.com/api/?Action=CreateUserPoolClient?ClientName=ClientName&ExplicitAuthFlows=ExplicitAuthFlows&GenerateSecret=GenerateSecret&ReadAttributes=ReadAttributes&RefreshTokenValidity=RefreshTokenValidity&UserPoolId=UserPoolId&WriteAttributes=WriteAttributes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates the user pool client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eac0302d-a3a6-4b24-80d6-d5f5377ea3cb"
            }
          ]
        },
        {
          "id": "44cc7b48-c25f-41ef-bae8-35b2667e26de",
          "name": "deleteUser",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUser?AccessToken=AccessToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows a user to delete one's self."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "49f12abd-2305-4a53-8c43-edd4f7aa6d23"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Up",
      "item": [
        {
          "id": "c8d23f5c-655d-4062-9e2f-7a93c465b546",
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
              "id": "19034d7e-eaf1-4ead-ab4b-5065d98ad39d"
            }
          ]
        }
      ]
    },
    {
      "name": "Devices",
      "item": [
        {
          "id": "f66310d1-98a6-4f24-a85d-836679ae8f9e",
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
              "id": "6efc0b14-bb34-4869-b897-5cdddbfba319"
            }
          ]
        },
        {
          "id": "ecb7bf45-c3ff-4224-a239-0108304d68bb",
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
              "id": "72d419f4-808f-4ff8-aa28-ce92b5bcabd1"
            }
          ]
        }
      ]
    },
    {
      "name": "http://laneworks.net/api-stack/pull/pull-amazon-cognito-sync.php",
      "item": [
        {
          "id": "54ac10f5-51e7-4817-96ec-e882c718baf8",
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
              "id": "a4f01510-3586-4403-aa74-9bc1fd4c3771"
            }
          ]
        },
        {
          "id": "6a174fd2-48e1-491b-a2ee-79bf233a5b26",
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
              "id": "d33572ba-7683-41d7-b0d9-181f22a7ddfe"
            }
          ]
        }
      ]
    },
    {
      "name": "Authnetication",
      "item": [
        {
          "id": "7837fcd9-a482-4690-bc22-c51091c78c35",
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
              "id": "4f85e055-6298-4d11-97bd-e3c7ced8d174"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication Challenge",
      "item": [
        {
          "id": "d8cdd46b-9273-48c0-997b-727b14f65fcc",
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
              "id": "e3f7f212-ecfa-42d0-8826-4f3b8ef378ac"
            }
          ]
        }
      ]
    },
    {
      "name": "Password",
      "item": [
        {
          "id": "ee6cd0bc-3a89-4571-b1bc-9d89633ffa4b",
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
              "id": "a1cbf0e6-6cdf-4759-98f0-da2a12e121a3"
            }
          ]
        }
      ]
    },
    {
      "name": "Passwords",
      "item": [
        {
          "id": "3cbb079c-f830-456d-944e-cd01ed6970dc",
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
              "id": "a82871fe-bbae-495d-8298-86e293297d38"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Ups",
      "item": [
        {
          "id": "0146d770-643a-4ac6-ba2a-cd14f74710f4",
          "name": "confirmSignUp",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmSignUp?ClientId=ClientId&ConfirmationCode=ConfirmationCode&ForceAliasCreation=ForceAliasCreation&SecretHash=SecretHash&Username=Username",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Confirms registration of a user and handles the existing alias from a previous\n            user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71ca89ac-9179-4428-a97b-fa37dbfb4071"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "b5f7c65f-754e-4fa1-b282-a3acda57e0ea",
          "name": "createGroup",
          "request": {
            "url": "http://example.com/api/?Action=CreateGroup?Description=Description&GroupName=GroupName&Precedence=Precedence&RoleArn=RoleArn&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new group in the specified user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6996a8bc-9b58-46c8-b2c5-f00be2a78061"
            }
          ]
        },
        {
          "id": "c451a245-5395-489b-9de9-558190da67bf",
          "name": "deleteGroup",
          "request": {
            "url": "http://example.com/api/?Action=DeleteGroup?GroupName=GroupName&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be6bb539-cc38-4854-8140-40fb21aea9c2"
            }
          ]
        }
      ]
    }
  ]
}