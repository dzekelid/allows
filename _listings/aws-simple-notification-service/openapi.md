swagger: "2.0"
x-collection-name: AWS Simple Notification Service
x-complete: 1
info:
  title: AWS Simple Notification Service API
  version: 1.0.0
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