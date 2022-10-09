# TestProdyct
тестовое задание по MS SQL
Скрипт на получение товаров и их категорий:

Select Prodyct.[name],[Type].[name] from Prodyct
Left join ProdyctType on Prodyct.Id=ProdyctType.ProdyctId
Left Join [Type] on [Type].id=ProdyctType.TypeId
