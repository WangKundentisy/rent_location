# rent_location
<html>
<h>获取房源信息（Get_house_info.py）</h>
<body>房源为:"http://bj.58.com/pinpaigongyu/pn/{page}/?minprice=2000_3000",其中page为页数</body>
<p>房源存在csv文件中</p>
<p>1.由于py3中，csv_file只支持文本文件，不支持二进制文件(py2中支持)，所以初始化为:csv_file = open("rent.csv","w") </p>
<p>2.bytes与str转化:</p>
<p>str->byte:str.encode(encoding)</p>
<p>byte->str:byte.decode(encoding)</p>
</html>
