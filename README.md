js-location
===========

中国的省市地区三级选择框

使用
-----
``` html
<script src="location.js"></script>

<div><label for="province">省份：</label><select id="province" name="province"></select></div>
<div><label for="city">城市：</label><select id="city" name="city"></select></div>
<div><label for="county">区县：</label><select id="county" name="county"></select></div>
<div><span id="address"></span></div>

<script>
	var loc = beva.locationutil.attach('province', 'city', 'county', 'address');
	
	// loc.setSelectedCodes([697,698]);
</script>

```

问题
----
location.js原始省市地区中，北京/上海/天津等地区无区县一级

致谢
----
感谢[淘宝网](http://taobao.com)，location.js代码是在[TB.form.DistrictSelector](http://a.tbcdn.cn/sys/js/districtselector.js) 基础上根据自身业务需求做了适当调整。