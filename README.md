# gitbook-plugin-tooltips

Tooltips Plugin for Gitbook

Add the plugin to your `book.json`:

```
{
	"plugins" : [ "tooltips" ]
}		
```

How to use it:

```
{% tooltips title="Tooltips" %}
[1]
{% endtooltips %}
```

```
# 《垓下歌》

力拔山兮气盖世{% tooltips title="盖世：言笼盖一世。这句诗说自己的体力和勇气过人。" %}(1){% endtooltips %}，时不利兮骓不逝{% tooltips title="骓（音锥）：青白杂毛的马。不逝：言困在重围，不得去。逝，行。" %}(2){% endtooltips %}。

骓不逝兮可奈何，虞兮虞兮奈若何{% tooltips title="虞：女子名，项籍的侍姬。奈若何：是说把你怎么处置呢。若，犹“汝”。" %}(3){% endtooltips %}！

**【注释】**

(1)盖世：言笼盖一世。这句诗说自己的体力和勇气过人。

(2)骓（音锥）：青白杂毛的马。不逝：言困在重围，不得去。逝，行。

(3)虞：女子名，项籍的侍姬。奈若何：是说把你怎么处置呢。若，犹“汝”。
```
