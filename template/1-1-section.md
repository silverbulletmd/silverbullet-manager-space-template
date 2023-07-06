---
$disableDirectives: true
---

## Performance reviews
<!-- #query page where name =~ /{{@page.name}}\/Review/ select name render [[template/page]] -->

<!-- /query -->

## Incoming tasks
<!-- #query task where name =~ /{{escapeRegexp @page.name}}/ where done = false render [[template/task]] -->

<!-- /query -->
