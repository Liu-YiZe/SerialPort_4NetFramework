# SerialPort_4NetFramework
<p>2019-06-06</p>
<p>这是基于.Net Framework 4.0，封装了串口一些操作，如打开串口、关闭串口、串口发送、串口接收等，方便下次需要使用串口功能时，直接在解决方案中添加该类库。可以直接调取使用。</p>

<p>目前完成功能：</p>
<p>1、打开串口</p>
<p>2、关闭串口</p>
<p>3、广播串口收到的消息</p>
<p>4、发送串口数据</p>

<p>注意事项：</p>
<p>需要订阅 串口接收数据事件，才可以接收到串口数据。</p>
<p>该类库的编译器是Visual Studio 2010，框架是.Net Framework 4.0</p>

<p>2019-09-17</p>
<p>新增功能：</p>
<p>1、可以获取当前系统下的串口资源</p>
<p>2、提供波特率列表接口</p>