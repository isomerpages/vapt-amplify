---
title: This title should not matter
permalink: /example-folder/example-subfolder/permalink/
description: ""
third_nav_title: <script>alert('xss test 3')</script>
---
<xss onafterscriptexecute=alert(1)><script>1</script>
<body onMouseOver body onMouseOver="javascript:javascript:alert(1)"></body onMouseOver>