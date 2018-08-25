---
swagger: "2.0"
x-collection-name: AWS Simple Notification Service
x-complete: 0
info:
  title: AWS Simple Notification Service API Set Subscription Attributes
  version: 1.0.0
  description: Allows a subscription owner to set an attribute of the topic to a new
    value.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=SetSubscriptionAttributes:
    get:
      summary: Set Subscription Attributes
      description: Allows a subscription owner to set an attribute of the topic to
        a new value.
      operationId: setSubscriptionAttributes
      x-api-path-slug: actionsetsubscriptionattributes-get
      parameters:
      - in: query
        name: AttributeName
        description: The name of the attribute you want to set
        type: string
      - in: query
        name: AttributeValue
        description: The new value for the attribute in JSON format
        type: string
      - in: query
        name: SubscriptionArn
        description: The ARN of the subscription to modify
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subscriptions
  /?Action=SetTopicAttributes:
    get:
      summary: Set Topic Attributes
      description: Allows a topic owner to set an attribute of the topic to a new
        value.
      operationId: setTopicAttributes
      x-api-path-slug: actionsettopicattributes-get
      parameters:
      - in: query
        name: AttributeName
        description: The name of the attribute you want to set
        type: string
      - in: query
        name: AttributeValue
        description: The new value for the attribute
        type: string
      - in: query
        name: TopicArn
        description: The ARN of the topic to modify
        type: string
      responses:
        200:
          description: OK
      tags:
      - Topics
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