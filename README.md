# -
常见问题随笔

1.TextView 使用xml 指定文字大小（暂无效果）/颜色/占位符
  xml中：
  <string name="str">"<Data><![CDATA[<font size="15" color="#969696">字符串</font><font size="2" color="#fe6900">测试</font><font size="15" color="#fe6900">"%1$s"</font>]]></Data>"</string>
  
  代码中：
  Spanned str = Html.fromHtml(getResources().getString(R.string.str,"完成"))；
  
  效果：字符串测试完成
  
#
  

