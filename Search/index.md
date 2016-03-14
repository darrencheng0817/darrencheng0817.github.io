title: Search
date: 2016-03-13 10:12:44
---
## Search what you want
<div style="text-align: center">
	<input type="text" id="local-search-input" name="q" results="0" placeholder="Search articles here!" class="search-input">
</div>
<div id="local-search-result"></div>
<script src="/js/search.js"></script> 
<script type="text/javascript">      
 var path = "/search.xml";
 searchFunc(path, 'local-search-input', 'local-search-result');
</script>