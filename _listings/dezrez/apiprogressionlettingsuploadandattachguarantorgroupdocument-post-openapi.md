---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Allows you to upload a lettings document and attach it directly to
    a guarantor group.
  version: 1.0.0
  description: Allows you to upload a lettings document and attach it directly to
    a guarantor group..
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/coreplatformstate/platformissue:
    post:
      summary: Allows business workflows to post system issues to the platform state
        service.
      description: Allows business workflows to post system issues to the platform
        state service..
      operationId: CorePlatformState_PostPlatformIssueByalertDataContract
      x-api-path-slug: apicoreplatformstateplatformissue-post
      parameters:
      - in: body
        name: alertDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - Business
      - Workflows
      - To
      - Post
      - System
      - Issues
      - To
      - Platform
      - State
      - Service
  /api/progression/lettings/uploadandattachtenantdocument:
    post:
      summary: Allows you to upload a document and attach it directly to a tenant.
      description: Allows you to upload a document and attach it directly to a tenant..
      operationId: LettingsProgression_UploadAndAttachTenantDocumentBytenantInfoIdBydocumentDetailsContract
      x-api-path-slug: apiprogressionlettingsuploadandattachtenantdocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: tenantInfoId
        description: The tenant Id
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Tenant
  /api/progression/lettings/uploadandattachlandlorddocument:
    post:
      summary: Allows you to upload a document and attach it directly to a tenant.
      description: Allows you to upload a document and attach it directly to a tenant..
      operationId: LettingsProgression_UploadAndAttachLandlordDocumentBylandlordInfoIdBydocumentDetailsContract
      x-api-path-slug: apiprogressionlettingsuploadandattachlandlorddocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: landlordInfoId
        description: The tenant Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Tenant
  /api/progression/lettings/uploadandattachguarantorgroupdocument:
    post:
      summary: Allows you to upload a lettings document and attach it directly to
        a guarantor group.
      description: Allows you to upload a lettings document and attach it directly
        to a guarantor group..
      operationId: LettingsProgression_UploadAndAttachGurantorGroupDocumentByguarantorGroupIdBytenancyIdBydocumentDetai
      x-api-path-slug: apiprogressionlettingsuploadandattachguarantorgroupdocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: guarantorGroupId
        description: The guarantor group Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: tenancyId
        description: The tenancy Id
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Lettings
      - Document
      - Attach
      - It
      - Directly
      - To
      - Guarantor
      - Group
  /api/progression/lettings/uploadandattachguarantordocument:
    post:
      summary: Allows you to upload a document and attach it directly to a guarantor.
      description: Allows you to upload a document and attach it directly to a guarantor..
      operationId: LettingsProgression_UploadAndAttachGuarantorDocumentByguarantorIdBydocumentDetailsContract
      x-api-path-slug: apiprogressionlettingsuploadandattachguarantordocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: guarantorId
        description: The guarantor Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Guarantor
  /api/progression/lettings/uploadandattachguarantorreferencedocument:
    post:
      summary: Allows you to upload a document and attach it directly to a guarantor.
      description: Allows you to upload a document and attach it directly to a guarantor..
      operationId: LettingsProgression_UploadAndAttachGuarantorReferenceDocumentByguarantorIdByreferenceIdBydocumentDet
      x-api-path-slug: apiprogressionlettingsuploadandattachguarantorreferencedocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: guarantorId
        description: The guarantor Id
      - in: query
        name: referenceId
        description: The reference Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Guarantor
  /api/progression/lettings/uploadandattachrighttorentdocument:
    post:
      summary: Allows you to upload a document and attach it directly to a r ight
        to rent.
      description: Allows you to upload a document and attach it directly to a r ight
        to rent..
      operationId: LettingsProgression_UploadAndAttachRightToRentDocumentBytenantInfoIdBydocumentDetailsContract
      x-api-path-slug: apiprogressionlettingsuploadandattachrighttorentdocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: tenantInfoId
        description: The tenant info Id
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - R
      - Ight
      - To
      - Rent
  /api/progression/lettings/uploadandattachtenantreferencedocument:
    post:
      summary: Allows you to upload a document and attach it directly to a guarantor.
      description: Allows you to upload a document and attach it directly to a guarantor..
      operationId: LettingsProgression_UploadAndAttachTenantReferenceDocumentBytenantInfoIdByreferenceIdBytenantRoleIdB
      x-api-path-slug: apiprogressionlettingsuploadandattachtenantreferencedocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: referenceId
        description: The reference Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: tenantInfoId
        description: The tenantInfoId Id
      - in: query
        name: tenantRoleId
        description: The reference Id
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Guarantor
  /api/milestone/{id}/uploadandattachdocument:
    post:
      summary: Allows you to upload a document and attach it directly to a milestone.
      description: Allows you to upload a document and attach it directly to a milestone..
      operationId: Milestone_UploadAndAttachDocumentByidBydocumentDetailsContract
      x-api-path-slug: apimilestoneiduploadandattachdocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        description: Document save command
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The milestone Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Milestone
  /api/negotiator/my/preferences/emailsignature:
    post:
      summary: Allows you to upload a document for use as email signature
      description: Allows you to upload a document for use as email signature.
      operationId: Negotiator_UploadEmailSignatureBydocumentDetailsContract
      x-api-path-slug: apinegotiatormypreferencesemailsignature-post
      parameters:
      - in: body
        name: documentDetailsContract
        description: Document details
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Documentuse
      - As
      - Email
      - Signature
  /api/property/{id}/uploadandattachdocument:
    post:
      summary: Allows you to upload a document and attach it directly to a property.
      description: Allows you to upload a document and attach it directly to a property..
      operationId: Property_UploadAndAttachDocumentByidBydocumentDetailsContract
      x-api-path-slug: apipropertyiduploadandattachdocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        description: Details o
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The property Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Property
  /api/property/uploadandattachcertificatedocument:
    post:
      summary: Allows you to upload a document and attach it directly to a guarantor.
      description: Allows you to upload a document and attach it directly to a guarantor..
      operationId: Property_UploadAndAttachCertificateDocumentBycertificateIdBydocumentDetailsContract
      x-api-path-slug: apipropertyuploadandattachcertificatedocument-post
      parameters:
      - in: query
        name: certificateId
        description: The Certificate Id
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Guarantor
  /api/role/{id}/uploadandattachdocument:
    post:
      summary: Allows you to upload a document and attach it directly to a role.
      description: Allows you to upload a document and attach it directly to a role..
      operationId: Role_UploadAndAttachDocumentByidBydocumentDetailsContract
      x-api-path-slug: apiroleiduploadandattachdocument-post
      parameters:
      - in: body
        name: documentDetailsContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Document
      - Attach
      - It
      - Directly
      - To
      - Role
  /api/roomdescription/setimages:
    post:
      summary: Allows you to specify a list of documentIds for a roomDescriptions
        room - this list will overwrite any existing list of documents on that room,
        and order will be honoured.
      description: Allows you to specify a list of documentids for a roomdescriptions
        room - this list will overwrite any existing list of documents on that room,
        and order will be honoured..
      operationId: RoomDescription_SetImagesByroomImageOrder
      x-api-path-slug: apiroomdescriptionsetimages-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: roomImageOrder
        description: The room image order
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Specify
      - List
      - Of
      - DocumentIdsa
      - RoomDescriptions
      - Room
      - '-'
      - This
      - List
      - Will
      - Overwrite
      - Any
      - Existing
      - List
      - Of
      - Documents
      - "On"
      - That
      - Room
      - ""
      - Order
      - Will
      - Be
      - Honoured
  /api/OccupierAllowanceDescription/{id}:
    get:
      summary: ""
      description: .
      operationId: OccupierAllowanceDescription_GetByid
      x-api-path-slug: apioccupierallowancedescriptionid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - ""
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---