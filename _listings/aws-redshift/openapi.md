swagger: "2.0"
x-collection-name: AWS Redshift
x-complete: 1
info:
  title: AWS Redshift API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=PurchaseReservedNodeOffering:
    get:
      summary: Purchase Reserved Node Offering
      description: Allows you to purchase reserved nodes.
      operationId: purchaseReservedNodeOffering
      x-api-path-slug: actionpurchasereservednodeoffering-get
      parameters:
      - in: query
        name: NodeCount
        description: The number of reserved nodes that you want to purchase
        type: string
      - in: query
        name: ReservedNodeOfferingId
        description: The unique identifier of the reserved node offering you want
          to purchase
        type: string
      responses:
        200:
          description: OK
      tags:
      - Reserved Nodes