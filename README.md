Caracter especial no Marketing Cloud da Salesforce

A linha abaixo simula as situações aceitas pelo Marketing Cloud
Use em uma De de texte para limpar os caracteres conforme o CHAR(_exemple_) ''

!"#$%&'()*+,-./0123456789:;<=>?@ABCDEFGHIJKLMNOPQRSTUVWXYZ[\]^_`abcdefghijklmnopqrstuvwxyz{|}~¡¢£¤¥¦§̈¨©ª«¬®̄¯°±²³́´μ¶·̧¸¹º»1⁄41⁄23⁄4¿ÀÁÂÃÄÅÆÇÈÉÊËÌÍÎÏÐÑÒÓÔÕÖ×ØÙÚÛÜÝÞßàáâãäåæçèéêëìíîïðñòóôõö÷øùúûüýþÿ

Source: https://help.salesforce.com/s/articleView?id=sf.mc_es_ascii_characters.htm&type=5


Até o momento usando o arquivo "caracter especial todos" o resultado da limpeza obtido foi --> 0456789@ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz§¨®¯³´µ·¸/4//4

Nota-se a exclusão do 1 2 3, porém precisa também eliminar de forma certa os caracters após o "z". 

ps.: a exclusão do 1 2 3 está relacionado a exclusão dos números ¹²³ 
