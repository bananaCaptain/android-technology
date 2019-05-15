svn 忽略文件设置 
https://www.cnblogs.com/Claire6649/p/6090745.html



workspace.xml 文件下添加以下内容，然后再进行首次提交


<component name="ChangeListManager">
    <list default="true" readonly="true" id="a0e97fd6-7285-4ee1-8a57-0f7ca669f55e" name="Default" comment="">
      <change beforePath="$PROJECT_DIR$/app/src/main/res/drawable/tab_tv_bg_shape.xml" beforeDir="false" afterPath="$PROJECT_DIR$/app/src/main/res/drawable/tab_tv_bg_shape.xml" afterDir="false" />
      <change beforePath="$PROJECT_DIR$/app/src/main/res/layout/fragment_about.xml" beforeDir="false" afterPath="$PROJECT_DIR$/app/src/main/res/layout/fragment_about.xml" afterDir="false" />
    </list>
    <ignored mask="*.apk" />
    <ignored mask="*.ap_" />
    <ignored mask="*.dex" />
    <ignored mask="*.class" />
    <ignored mask="*.iml" />
    <ignored mask="*.log" />
    <ignored mask="*.jks" />
    <ignored mask="build" />
    <ignored mask="captures" />
    <ignored path="local.properties" />
    <ignored path=".gradle/" />
    <ignored path=".idea/" />
    <ignored path=".externalNativeBuild/" />
    <ignored path=".navigation/" />
