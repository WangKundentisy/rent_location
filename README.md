# rent_location
获取房源信息
1.由于py3中，csv_file只支持文本文件，不支持二进制文件(py2中支持)，所以初始化为:csv_file = open("rent.csv","w") 
2.bytes与str转化:
str->byte:str.encode(encoding)
byte->str:byte.decode(encoding)
