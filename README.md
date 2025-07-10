简介v1 网址：https://gopeed.com许可证： MIT 这是 gopeed RESTful API 文档。您可以使用此 API 来管理下载任务。

响应格式 所有API均返回JSON 格式响应。响应格式为：

{ "code": 0, "message": "", "data": null } code：响应码，0表示成功，其他值表示错误。 message：响应信息，如果code!= 0，则该字段将包含错误消息。 data：响应数据，如果code== 0，则该字段将包含响应数据。
