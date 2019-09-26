svn 忽略文件设置 
https://www.cnblogs.com/Claire6649/p/6090745.html



workspace.xml 文件下添加以下内容，然后再进行首次提交


<component name="ChangeListManager">
    <list default="true" id="8ac7d056-1584-4a90-97e4-b25f41093ecc" name="Default Changelist" comment="" />
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
    <option name="EXCLUDED_CONVERTED_TO_IGNORED" value="true" />
    <option name="SHOW_DIALOG" value="false" />
    <option name="HIGHLIGHT_CONFLICTS" value="true" />
    <option name="HIGHLIGHT_NON_ACTIVE_CHANGELIST" value="false" />
    <option name="LAST_RESOLUTION" value="IGNORE" />
  </component>
  <component name="ExternalProjectsData">
    <projectState path="$PROJECT_DIR$">
      <ProjectState />
    </projectState>
  </component>
  
  注意：这里需要打开编辑才能看到内容
