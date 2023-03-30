
<div align=center><img src="icons/edrawingbar.png" width="200"/></div>

![lang](https://img.shields.io/badge/language-csharp-green.svg)
![Github](https://img.shields.io/badge/Github-build-blue.svg?style=flat-square)
![Github](https://img.shields.io/badge/Nuget-v1.0.1-yellowgreen.svg?style=flat-square)


# DuEDrawingControl

[English]((https://github.com/weianweigan/DuEDrawingControl/blob/master/README.md)) | ����

��Winform��wpf��ʹ�õ�edrawing �ؼ���ʹ����c# dynamic ���ͷ�װ�������Ͳ���Ҫ����edrawing��dll������Ҫ�������ã�ֱ�����ñ����ʹ�á�

**Winform:**

<div align=left><img src="icons/winform.png" width="400"/></div>

���Ӳ�����ť��2023.3.29��
<div align=left><img src="icons/winform_2.png" width="400"/></div>


**WPF**

<div align=left><img src="icons/wpf.png" width="400"/></div>

**PreView Assembly Document**

<div align=left><img src="./icons/assembly.png" width="400"/></div>

**PreView Drawing Document**

<div align=left><img src="./icons/drawing.png" width="400"/></div>

**Print Document**

<div align=left><img src="./icons/print.png" width="400"/></div>

**Create ToolTip**

<div align=left><img src="./icons/tooltip.png" width="400"/></div>

## ��װ


```
Install-Package DuEDrawingControl -Version 1.0.1
```


## ʹ��

**1.��Ҫ��װeDrawing**

**2.���������ռ�**
```csharp
using DuEDrawingControl;
```

**3.��ƽ̨�޸�Ϊx64**

<div align=left><img src="./icons/x64.png" width="400"/></div>

**4.��ӿؼ�**

### Winform

```csharp

        private EDrawingView eDrawingView;

        private void Form1_Load(object sender, EventArgs e)
        {
            //add edrawing control when form loaded
            eDrawingView = new EDrawingView()
            {
                Dock = DockStyle.Fill
            };
            paneleDrawing.Controls.Add(eDrawingView);
        }

```

Clone this repository for more

### WPF

```csharp
        private DuEDrawingControl.EDrawingWPFControl edrawing;

        public MainWindow()
        {
            InitializeComponent();

            //Add edrawing control
            edrawing = new DuEDrawingControl.EDrawingWPFControl() { 
                Margin = new Thickness(5)
            };
            edrawingPanel.Children.Add(edrawing);
        }
```

Clone this repository for more

## ʾ��

![](./icons/example.png)

## ʵ�ֵ�edrawing api

![api](./icons/api.png)

![api_Markup](./icons/api_Markup.png)

## Contact me

1831197727@qq.com