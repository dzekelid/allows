---
swagger: "2.0"
x-collection-name: AWS ElastiCache
x-complete: 0
info:
  title: Amazon ElastiCache API Purchase Reserved Cache Nodes Offering
  version: 1.0.0
  description: |-
    Allows you to purchase a reserved
                cache node offering.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AuthorizeCacheSecurityGroupIngress:
    get:
      summary: Authorize Cache Security Group Ingress
      description: |-
        Allows network ingress to a cache
                    security group.
      operationId: authorizeCacheSecurityGroupIngress
      x-api-path-slug: actionauthorizecachesecuritygroupingress-get
      parameters:
      - in: query
        name: CacheSecurityGroupName
        description: The cache security group that allows network ingress
        type: string
      - in: query
        name: EC2SecurityGroupName
        description: The Amazon EC2 security group to be authorized for ingress to
          the cache security group
        type: string
      - in: query
        name: EC2SecurityGroupOwnerId
        description: The AWS account number of the Amazon EC2 security group owner
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Security Groups
  /?Action=PurchaseReservedCacheNodesOffering:
    get:
      summary: Purchase Reserved Cache Nodes Offering
      description: |-
        Allows you to purchase a reserved
                    cache node offering.
      operationId: purchaseReservedCacheNodesOffering
      x-api-path-slug: actionpurchasereservedcachenodesoffering-get
      parameters:
      - in: query
        name: CacheNodeCount
        description: The number of cache node instances to reserve
        type: string
      - in: query
        name: ReservedCacheNodeId
        description: A customer-specified identifier to track this reservation
        type: string
      - in: query
        name: ReservedCacheNodesOfferingId
        description: The ID of the reserved cache node offering to purchase
        type: string
      responses:
        200:
          description: OK
      tags:
      - Reserved Cache Nodes
  /?Action=ListAllowedNodeTypeModifications:
    get:
      summary: List Allowed Node Type Modifications
      description: |-
        Lists all available node types that you
                    can scale your Redis cluster's or replication group's current node type up to.
      operationId: listAllowedNodeTypeModifications
      x-api-path-slug: actionlistallowednodetypemodifications-get
      parameters:
      - in: query
        name: CacheClusterId
        description: The name of the cache cluster you want to scale up to a larger
          node instanced type
        type: string
      - in: query
        name: ReplicationGroupId
        description: The name of the replication group want to scale up to a larger
          node type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Node Type Modifications
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