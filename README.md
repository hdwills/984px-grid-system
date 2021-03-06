984px-grid-system
=================

* 984px total width, 974px wide with 10px side margins
* 12 columns at 72px, 10px gutters

-------------------------------------------------------------------

目前手头上的站，设计都比较中规中矩的。之前一直用的 [960.gs](http://960.gs)，但是目前这个高分辨率、宽屏流行的时代，总感觉 960px 有些太窄，是不是在内容的显示上太过于局限。

曾在知乎上有过提问：[960px 宽度的网格布局过时了吗？](http://www.zhihu.com/question/20088948)  
大家也都给出了相应的看法的想法，也有在 960px 基础上扩展的。
> 「让一屏显示更多的量」从来都不是网页设计的目的，网络是用来传递信息的，又不是囤积信息  
> via -[设计时如何选择合适的字号？](http://www.zhihu.com/question/19629822) @梁海

-------------------------------------------------------------------

后来找到了 [978.gs](http://978.gs/)，这个 grid system 里面包括了针对不同分辨率的终端上的解决方案

* Browser Specs
> 1. Desktop, Tablet, Phone  
> 2. 1378 grid system, 1218 grid system, 978 grid system, 748 grid system, 300 grid system  
> 3. with responsive design
> 4. 12 columns, 30px gutters

* 看了之后发现，30px 的间隙，似乎在我的实际应用中显得过宽了。

-------------------------------------------------------------------

再后来，就自己动手吧。
借助 [Variable Grid System](http://grids.heroku.com/) - Variable Grid System 0.6 designed & developed by SprySoft, Based on 960 Grid System  
做了适当的调整，就改成了目前所在使用的这个 984px grid system

实际应用中部署了一个简单的企业站
> 984px total width, 974px wide with 10px side margins  
> 12 columns at 72px, 10px gutters

在实际应用之后，才发现。其实适当的留白能更好的衬托页面的实体内容，再加上得当的排版，让整个页面精致又耐看。所以这个 grid system 就算是个练手项目，在实际应用中并不是那么理想，还需要更一步的调整和改进 :-)