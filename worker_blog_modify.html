// 定义 Github 项目，文章会从这里读取
const github_base = "a2396837/cloudflare-worker-blog";

// 设置站点信息
var default_title	 = "Dmx'的自留地";					// 站点标题（显示在浏览器标题栏）
var default_intitle	 = "Dmx'的自留地";								// 站点名称（显示在首页）
var default_description  = "欢迎来到Dmx'的自留地，分享生活！"; 	// 站点简介，有利于 SEO
var site_domain		 = "blog.dmx.best";								// 站点域名
var site_subtitle	 = "💒主站：https://dmx.pub";							// 站点副标题
var site_favicon	 = "https://cdn.jsdelivr.net/gh/a2396837/CDN@latest/images/2020/08/04/2886b86c544d2a0c08515ba8242d940a.png";				// 站点 Logo

// 博主信息
var owner_name = "Dmx";									// 博主名字
var owner_logo = "https://cdn.jsdelivr.net/gh/a2396837/CDN@latest/images/2020/07/27/baokemeng.webp"	// 博主头像
var owner_desc = "Do what you love,love what you do.";					// 博主简介

// 设置站点资源文件地址
var css_bootstrap	 = "https://cdn.jsdelivr.net/npm/bootstrap@4.5.0/dist/css/bootstrap.min.css";	// Boostrap css 文件地址
var css_hljs_github   = "https://cdn.jsdelivr.net/gh/highlightjs/cdn-release@10.1.2/build/styles/tomorrow.min.css";  // Highlight js css 地址
var js_jquery		 = "https://cdn.jsdelivr.net/npm/jquery@latest/dist/jquery.min.js";		// JQuery 地址
var js_bootstrap	= "https://cdn.jsdelivr.net/npm/bootstrap@4.5.0/dist/js/bootstrap.min.js";	// Bootstrap 地址
var js_instantclick   = "https://cdn.jsdelivr.net/npm/instantclick@3.1.0-2/dist/instantclick.min.js";	// InstantClick 地址
var js_showdown	 = "https://cdn.jsdelivr.net/npm/showdown@1.9.1/dist/showdown.min.js";		// Showdown 地址
var js_showdown_table = "https://cdn.jsdelivr.net/npm/showdown-table2@2.0.4/dist/showdown-table.min.js";	// Showdown table 地址
var js_highlight	= "https://cdn.jsdelivr.net/gh/highlightjs/cdn-release@10.1.2/build/highlight.min.js";	// Highlight 地址
var js_jquery_backstretch = "https://cdn.jsdelivr.net/npm/jquery-backstretch@2.1.17/jquery.backstretch.min.js";
var js_APlayer = "https://cdn.jsdelivr.net/npm/aplayer/dist/APlayer.min.js"
var css_Aplayer = "https://cdn.jsdelivr.net/npm/aplayer/dist/APlayer.min.css"
var js_Meting = "https://cdn.jsdelivr.net/npm/meting@2/dist/Meting.min.js"
var js_pjax = "https://cdn.jsdelivr.net/npm/pjax/pjax.js"

// 这是一些临时变量，无需修改
var title = "";
var intitle = "";
var title2 = "";
var description = "";
var ctime = "unknown";
var isunknown = "";

addEventListener('fetch', event => {
  event.respondWith(handleRequest(event.request))
});

var header = `<!DOCTYPE HTML>

<html lang="zh_CN">
	<head>
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
		<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
		<meta http-equiv="X-UA-Compatible" content="IE=11">
		<meta name="application-name" content="Dmx'的自留地">
		<meta name="msapplication-TileColor" content="#F1F1F1">
		<link rel="shortcut icon" href="${site_favicon}" />
		<meta name="description" content="{description}">
		<link rel="stylesheet" href="${css_bootstrap}" crossorigin="anonymous">
		<link rel="stylesheet" href="${css_hljs_github}">
		<link rel="stylesheet" href="${css_Aplayer}">
		<title>{title}{title_2}</title>
		<style type="text/css">code{color:#484848;background-color:#f5f5f5;border-radius:0px;border:1px solid #dadada;}pre>code{color:unset;background-color:unset;border-radius:unset;border:0px;}.post-a {color: #000;text-decoration: none ! important;}.post-box {padding: 12px 20px 12px 20px;border-bottom: 1px solid rgba(0,0,0,0.07);cursor: pointer;border-left: 0px solid rgba(66, 66, 66, 0);transition-duration: 0.3s;margin-top: 12px;border-radius: 8px;background: rgb(255 255 255 / 39%);}.post-box:hover {transition-duration: 0.3s;border-left: 5px solid rgb(176 219 253);-webkit-box-shadow: 0 4px 12px 12px rgba(7,17,27,.15);box-shadow: 0 4px 12px 12px rgba(7,17,27,.15);}.thread h2 {border-bottom: 1px solid rgb(238,238,238);padding-bottom: 10px;}.editor-preview pre, .editor-preview-side pre{padding: 0.5em;}.hljs{background: unset ! important;padding: 0px;}.CodeMirror{height: calc(100% - 320px);min-height: 360px;}.msgid{font-family:Consolas;}.tooltip {word-break: break-all;}h2 a{font-weight: 400;}body{font-family:-apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Lato, Roboto, "PingFang SC", "Microsoft JhengHei", "Microsoft YaHei", sans-serif ! important;font-weight:400;background-attachment:fixed;background-size:cover;background-repeat:no-repeat;background-position:center;}#bg{position: fixed; top: 0; left: 0; right: 0; bottom: 0; background-size: cover; background-position: top; background-repeat: no-repeat;}h2 a{color: #000;} h2 a:hover{color: #000; text-decoration: none;}.full-width{width: 100%;}.thread img{vertical-align:text-bottom ! important;max-width:100% ! important;margin-top:8px;margin-bottom:8px;}.thread table{display:block;width:100%;overflow:auto;margin-bottom:8px;}.thread table tr{background-color:#fff;border-top:1px solid #c6cbd1;}.thread table tr:nth-child(2n){background-color:#f7f7f7;}.thread table th,.thread table td{padding:10px 12px 0px 12px;border:1px solid #dfe2e5;font-size:14px;}.thread table th {padding-bottom: 10px;background: #f7f7f7;}.thread pre{margin-bottom:16px;}pre{border:none ! important;}blockquote{font-size:15px ! important;}@media screen and(max-width:768px){.copyright{text-align:center;}}.col-sm-3-1:hover{webkit-box-shadow: 0 4px 12px 12px rgba(7,17,27,.15);box-shadow: 0 4px 12px 12px rgba(7,17,27,.15);}.col-sm-3 img{max-width: 220px;width: 100%;border-radius: 50%;-webkit-transition: all .5s; -moz-transition: all .5s; -o-transition: all .5s; -ms-transition: all .5s; transition: all .5s;}.col-sm-3 img:hover{-webkit-transform:rotate(360deg);-moz-transform:rotate(360deg);-o-transform:rotate(360deg);-ms-transform:rotate(360deg);transform: rotate(360deg);}.col-sm-9{-webkit-box-shadow: 0 4px 12px 12px rgba(7,17,27,.15);box-shadow: 0 4px 12px 12px rgba(7,17,27,.15);background-color: hsla(0,0%,100%,.7);border-radius: 8px;}.col-sm-3-1{padding: 16px;text-align: center;border-radius: 8px;-webkit-box-shadow: 0 4px 12px 12px rgba(7,17,27,.15); box-shadow: 0 4px 12px 12px rgba(7,17,27,.15); background-color: hsla(0,0%,100%,.7);}.text-left{float:left}.col-sm-12{padding-top: 1em;}</style>
	</head>
	<body>
	    <div id="bg">
         <div class="backstretch"></div>
        </div>
		<div class="container">
			<div class="row">
				<div class="col-sm-12" id="body-wrap">
					<h2><a href="/" class="post-a">{intitle}</a></h2>
					<p>${site_subtitle}</p>
					<hr>
				</div>
				<div class="col-sm-9" id="body-wrap" style="padding-top: 2em;">
					<div class="thread">
												`;

						var modifyHeader = {};
						var cookieText = "";

						function getRequestParams(str) {
							var index = str.indexOf("?");
							str = str.substring(index + 1, str.length);
							if(typeof(str) == "string"){
								u = str.split("&");
								var get = {};
								for(var i in u){
									var j = u[i].split("=");

									get[j[0]] = j[1];
								}
								return get;
							} else {
								return {};
							}
						}

						async function bloghandle(request) {
							var cookie = {};
							var clist = undefined;
							try {
								cookieText.split(';').forEach(l => {
									var parts = l.split('=');
									cookie[parts[0].trim()] = unescape((parts[1] || '').trim());
								});
							} catch(e) {
								// 无可奉告
							}
							var $_GET = getRequestParams(request.url);
							var urls = new URL(request.url);
							var data = header;
							if(urls.pathname == "/") {
								var url = "https://raw.githubusercontent.com/" + github_base + "/master/list.json";
								const init = {
								method: "GET"
								};
								const response = await fetch(url, init);
								var resptxt = await response.text();
								if(cookie['list'] == undefined) {
									var Days = 30; 
									var exp = new Date(); 
									exp.setTime(exp.getTime() + Days*24*60*60*1000); 
									modifyHeader = {
										"Set-Cookie" : "list="+ escape (resptxt) + ";expires=" + exp.toGMTString()
									};
								}
								var json = JSON.parse(resptxt);
								// console.log(json);
								data += `<p>所有文章</p>
												`;
								var before_page = 0;
								var current_page = 1;
								var next_page = 2;
								var pagenow = json.length;
								var pageval = json.length - 5;
								if($_GET['p'] != undefined && $_GET['p'] != "") {
									pageval = json.length - (parseInt($_GET['p']) * 5);
									pagenow = json.length - ((parseInt($_GET['p']) - 1) * 5) - 1;
									next_page = parseInt($_GET['p']) + 1;
									current_page = parseInt($_GET['p']);
									before_page = parseInt($_GET['p']) - 1;
								}
								console.log(pageval);
								var update_i = 0;
								for(var i = pagenow;i >= pageval;i--) {
								try {
									var tmpfilename = encodeURIComponent(json[i].file
									.replace(/"/g, "").replace(/posts\//ig, "").replace(/\.md/ig, ""));
									var tmptime = json[i].time;
									var tmptitle = json[i].title;
									data += `<a href="/${tmpfilename}" class="post-a">
													<div class="post-box">
														<h4>${tmptitle}</h4>
														<p>发表于 ${tmptime}</p>
													</div>
												</a>
												`;
									update_i++;
								} catch(e) {
									// 收声
								}
								}
								console.log(update_i);
								if(update_i == 0) {
								data += `<p><blockquote>暂时没有文章！</blockquote></p>
										`
								}
								data += `<br>
												<p class="text-left pageid">当前在第 ${current_page} 页</p>
												<p class="text-right">
													`;
								if(current_page > 1) {
								data += `<a href="/?p=${before_page}"><button class="btn btn-default">上一页</button></a>&nbsp; &nbsp;`;
								}
								if(update_i >= 5) {
								data += `<a href="/?p=${next_page}"><button class="btn btn-default">下一页</button></a>`;
								}
								data += `
												</p>
											</div>
										`;
								title = default_title;
								intitle = default_intitle;
								title2 = "";
							} else {
								var uname = unescape("posts" + urls.pathname + ".md");
								try {
								clist = cookie['list'];
								} catch(e) {
								var url = "https://raw.githubusercontent.com/" + github_base + "/master/list.json";
								const init = {
									method: "GET"
								};
								const response = await fetch(url, init);
								clist = await response.text();
								}
								if(clist != undefined) {
									try {
										var json = JSON.parse(clist);
										var found = false;
										for(var i in json) {
											tmpfilename = json[i].file.replace(/"/g, "");
											tmptime = json[i].time;
											tmptitle = json[i].title;
											if(tmpfilename == uname) {
												title = tmptitle;
												intitle = tmptitle;
												ctime = tmptime;
												found = true;
											}
										}
										if(!found) {
											var url = "https://raw.githubusercontent.com/" + github_base + "/master/list.json";
											const init = {
												method: "GET"
											};
											const response = await fetch(url, init);
											clist = await response.text();
											var json = JSON.parse(clist);
											for(var i in json) {
												tmpfilename = json[i].file.replace(/"/g, "");
												tmptime = json[i].time;
												tmptitle = json[i].title;
												if(tmpfilename == uname) {
													title = tmptitle;
													intitle = tmptitle;
													ctime = tmptime;
												}
											}
											var Days = 30; 
											var exp = new Date(); 
											exp.setTime(exp.getTime() + Days*24*60*60*1000); 
											modifyHeader = {
												"Set-Cookie" : "list="+ escape (clist) + ";expires=" + exp.toGMTString()
											};
										}
									} catch(e) {
										// 收声
									}
								} else {
									var url = "https://raw.githubusercontent.com/" + github_base + "/master/list.json";
									const init = {
										method: "GET"
									};
									const response = await fetch(url, init);
									var clist = await response.text();
									var json = JSON.parse(clist);
									for(var i in json) {
										tmpfilename = json[i].file.replace(/"/g, "");
										tmptime = json[i].time;
										tmptitle = json[i].title;
										if(tmpfilename == uname) {
											title = tmptitle;
											intitle = tmptitle;
											ctime = tmptime;
										}
									}
									var Days = 30; 
									var exp = new Date(); 
									exp.setTime(exp.getTime() + Days*24*60*60*1000); 
									modifyHeader = {
										"Set-Cookie" : "list="+ escape (clist) + ";expires=" + exp.toGMTString()
									};
								}
								data += `</div>
												<p class="text-center{isunknown}"><small>发表于 ${ctime}</small></p>
												<textarea id="textdata" style="display: none;">`;
								var url = "https://raw.githubusercontent.com/" + github_base + "/master/posts" + urls.pathname + ".md";
								const init = {
									method: "GET"
								};
								const response = await fetch(url, init);
								if(response.status == 200) {
									var resptxt = await response.text();
									data += resptxt.replace(/&/g, "&amp;").replace(/</g, "&lt;").replace(/>/g, "&gt;");
									description = resptxt.substring(0, 128).replace(/"/ig, "").replace(/\n/g, " ");
									data += `</textarea>
											<hr>
										`;
								} else {
									data += `### 404 Not Found
						未找到您访问的页面，原因可能是：
						- 该文章已被删除
						- 该文章已经更改名称
						- 您输入的链接不正确

						<a href="/">返回 ${default_intitle} 首页</a>
											</textarea>
										`;
									title = `404 Not Found`;
									title2 = ` - ${default_title}`;
									intitle = `未找到指定的页面`;
									description = ``;
									isunknown = " hidden";
								}
								title2 = ` - ${default_title}`;
							}
							data += `</div>
				<div class="col-sm-3">
					<div class="col-sm-3-1">
						<img src="${owner_logo}" >
						<h3>${owner_name}</h3>
						<p class="text-center">${owner_desc}</p>
						<hr>
						<div class="text-center">
							<h4>友情链接</h4>
							<p><a href="https://dmx.pub/" target="_blank">主站</a></p>
						</div>
					</div>
				</div>
			</div>
			<div class="row">
				<div class="col-sm-12">
				<p>Powered by CloudFlare Workers | <a href="https://github.com/a2396837/cloudflare-worker-blog" target="_blank">Github</a></p>
				<p>&copy; 2020 ${default_intitle}</p>
				<br><br>
				</div>
			</div>
		</div>
		<div class="aplayer no-destroy" data-id="000PeZCQ1i4XVs" data-server="tencent" data-type="artist" data-fixed="true" data-mini="true" data-listFolded="false" data-order="random" data-preload="none" data-autoplay="true" muted></div>
		<script src="${js_jquery}"></script>
		<script src="${js_bootstrap}" crossorigin="anonymous"></script>
		<script src="${js_instantclick}" data-no-instant></script>
		<script src="${js_showdown}" type="text/javascript"></script>
		<script src="${js_showdown_table}" type="text/javascript"></script>
		<script src="${js_highlight}"></script>
		<script src="${js_jquery_backstretch}"></script>
		<script src="${js_APlayer}"></script>
		<script src="${js_Meting}"></script>
		<meting-js
			server="netease"
			type="playlist"
			id="60198"
			fixed="true">
		</meting-js>
		<script src="${js_pjax}"></script>
		<script> (function() {
			var t = [
			"https://cdn.jsdelivr.net/gh/a2396837/CDN@latest/images/2020/08/04/cfbg1.webp",
			"https://cdn.jsdelivr.net/gh/a2396837/CDN@latest/images/2020/08/04/zZxPjB9Z.webp",
			"https://cdn.jsdelivr.net/gh/a2396837/CDN@latest/images/2020/08/04/7vdoYEP4.webp",
			"https://cdn.jsdelivr.net/gh/a2396837/CDN@latest/images/2020/08/04/InXUuuL1.webp",
			"https://cdn.jsdelivr.net/gh/a2396837/CDN@latest/images/2020/08/04/OIkchljg.webp",
			"https://cdn.jsdelivr.net/gh/a2396837/CDN@latest/images/2020/08/04/8cYATHya.webp",
			"https://cdn.jsdelivr.net/gh/a2396837/CDN@latest/images/2020/08/04/HSGYlHNj.webp",
			"https://cdn.jsdelivr.net/gh/a2396837/CDN@latest/images/2020/08/04/cfbg6.webp",
			"https://cdn.jsdelivr.net/gh/a2396837/CDN@latest/images/2020/08/04/EupdGLc2.webp"
			];
			window.$("#bg").backstretch(t, {
				duration: 1e4,
				alignY: 0,
				transition: "fade",
				transitionDuration: 1e3
			})
		})()
		</script>
	   <div class="js-pjax">
		<script type="text/javascript">
			var init = {
			site: "${site_domain}",
			cid: "posts${urls.pathname}.md"
			};
			hljs.initHighlightingOnLoad();
			var md = new showdown.Converter({extensions: ['table']});
			md.setOption('simplifiedAutoLink', true);
			md.setOption('simpleLineBreaks', true);
			md.setOption('openLinksInNewWindow', true);
			md.setOption('noHeaderId', true);
			window.onload = function() {
				try {
					$(".thread").html(md.makeHtml($("#textdata").val()));
					document.querySelectorAll('pre code').forEach(function(e) {
						hljs.highlightBlock(e);
					});
					CommentsInit(comments, init);
				} catch(e) {}
			}
		</script>
		<script data-no-instant>
			InstantClick.init();
			InstantClick.on('change', function() {
				try {
					$(".thread").html(md.makeHtml($("#textdata").val()));
					document.querySelectorAll('pre code').forEach(function(e) {
						hljs.highlightBlock(e);
					});
					CommentsInit(comments, init);
				} catch(e) {}
			});
		</script>
	  </div>
		<script>
		   var pjax = new Pjax({
             elements: 'a:not([target="_blank"])',
			    selectors: [
				"title",
				"meta[name=description]",
				"#body-wrap",
				".js-pjax"
				],
				cacheBust: false,
		   });
		</script>
	</body>
</html>
	`;
	data = data.replace(/\{title\}/ig, title)
		.replace(/\{intitle\}/ig, intitle)
		.replace(/\{title\_2\}/ig, title2)
		.replace(/\{isunknown\}/ig, isunknown)
		.replace(/\{description\}/ig, description);
	return data;
}

/**
 * Respond to the request
 * @param {Request} request
 */
async function handleRequest(request) {
	if(new URL(request.url).protocol != "https:") {
		var rhttps = new Response("Location to https", {status: 301});
		rhttps.headers.set("Location", request.url.replace("http://", "https://"));
		return rhttps;
	}
	cookieText = request.headers.get("cookie");
	var resp = new Response(await bloghandle(request), {status: 200});
	resp.headers.set("Content-Type", "text/html");
	if(modifyHeader != undefined) {
		for(var index in modifyHeader) {
		resp.headers.set(index, modifyHeader[index]);
		}
	}
	return resp;
}