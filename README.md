# Bootstrap-WPF
使用 https://github.com/ptddqr/bootstrap-wpf-style 抽取为dll
# 示例 
## app.xmal中，引用dll中定义的风格资源文件
    <Application.Resources>
        <ResourceDictionary>
            <ResourceDictionary.MergedDictionaries>
                <ResourceDictionary Source="pack://application:,,,/Bootstrap-WPF;component/Styles/Bootstrap.xaml"/>
                <ResourceDictionary Source="pack://application:,,,/Bootstrap-WPF;component/PathGeometries/Glyphicons.xaml"/>
            </ResourceDictionary.MergedDictionaries>
        </ResourceDictionary>
    </Application.Resources>
    
## 使用bootstrap的定义值，如下的btn-primary
    <Button Content="Button" Style="{DynamicResource btn-primary}"/>
    
