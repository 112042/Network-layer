<!--index.html-->
<!DOCTYPE html>
<html>
    <title>計概檢討</title>
    <style>
        table {
          font-family: arial, sans-serif;
          border-collapse: collapse;
          width: 100%;
        }
        
        td, th {
          border: 1px solid #dddddd;
          text-align: left;
          padding: 8px;
        }
        
        tr:nth-child(even) {
          background-color: #dddddd;
        }
    </style>

<head><h1>網頁成績與檢討</h1></head>
<body>
    <p><h2>Tcp/Ip基本架構(Basic network architecture)</h2></p>
    <table>
        <tr>
          <th>TCP/IP LAYER</th>
          <th>Transmission unit</th>
          <th>Protocol</th>
          <th>Addressing</th>
          <th>Device</th>
          <th>OSI 7 layers</th>
        </tr>

        <tr>
          <td>Application Layer</td>
          <td>Data</td>
          <td>FTP,HTTP,HTTPS,SMTP,POP3</td>
          <td>HTTP(URL)</td>
          <td>Gateway</td>
          <td>Application,Presentation,Session</td>
        </tr>
       
        <tr>
            <td>Transport Layer</td>
            <td>Segment(Data gram)</td>
            <td>TCP,UPD,IPX</td>
            <td>Port Number</td>
            <td></td>
            <td>Transport</td>
        </tr>

        <tr>
            <td>Network Layer</td>
            <td>Packet</td>
            <td>IP,ARP,RARP,SPX,ICMP</td>
            <td>IP address(IPv4 or IPv6)</td>
            <td>Router</td>
            <td>Network</td>
          
          <td></td>
        </tr>

        <tr>
            <td>DataLink Layer</td>
            <td>Frame</td>
            <td>wired:802.3,802.4,802.5<br> wireless:802.11</td>
            <td>Bridge(switch)</td>
            <td>MAC Address</td>
            <td>DataLink Layer</td>
            
        </tr>
        
        <tr>
            <td>Physical Layer</td>
            <td>Bit</td>
            <td></td>
            <td></td>
            <td>Repeater(hub)</td>
            <td>Physical Layer</td>
        </tr> 
      </table>
      
      <p><h2>OSI 7 layers and TCP/IP architecture</h2></p>

    <table>
        <tr>
          <th>OSI 7 Layer</th>
          <th>Features</th>
          <th>功能特色</th>
          <th>TCP/IP Layer</th>
          <th>TCP/IP Layer</th>
        </tr>

        <tr>
          <td>Application Layer</td>
          <td>Provide a complete service<br>(including the structure of each layer)</td>
          <td>提供完整的服務(含有各層的架構)</td>
          <td>Application Layer</td>
          <td>Application Layer</td>
        </tr>

        
        <tr>
            <td>Presentation Layer</td>
            <td>(1). Internal code conversion<br>(2). Encryption/decryption<br>(3) Compression/decompression office</td>
            <td>(1).內碼轉換<br>(2).加/解密<br>(3).壓縮/解壓所)</td>
            <td>Application Layer</td>
            <td>Application Layer</td>
          </tr>

          
        <tr>
            <td>Session Layer</td>
            <td>(1). Communication before connection<br>(2). Establish a transmission channel between both parties</td>
            <td>(1).連線前的溝通<br>(2).建立雙方的傳輸通道</td>
            <td>Application Layer</td>
            <td>Application Layer</td>
          </tr>
       
        <tr>
            <td>Transport Layer</td>
            <td>(1). Flow control<br>(2). Error detection and handling<br>(3). Provide end-to-end transmission</td>
            <td>(1).流量控管<br>(2).錯誤偵測與處理<br>(3).提供終端與終端的傳輸</td>
            <td>Transport Layer</td>
            <td>Transport Layer</td>
        </tr>

        <tr>
            <td>Network Layer</td>
            <td>(1). Addressing: Assign the name or location of the network device<br>(2). Routing: select the transmission path</td>
            <td>(1).定址:賦予網路裝置名稱或位置<br>(2).路由:選擇傳送路徑</td>
            <td>Network Layer</td>
            <td>Network Layer</td>
        </tr>

        <tr>
            <td>DataLink Layer</td>
            <td>(1). Synchronization of sending and receiving<br>(2). Error control<br>(3). Provide point-to-point transmission</td>
            <td>(1).收送同步化<br>(2).錯誤控制<br>(3).提供點對點傳輸</td>
            <td>DataLink Layer</td>
            <td>Physical Layer</td>
        </tr>
        
        <tr>
            <td>Physical Layer</td>
            <td>(1). Wire<br>(2). Signal transmission</td>
            <td>(1).線材<br>(2).訊號傳送</td>
            <td>Physical Layer</td>
            <td>Physical Layer</td>
        </tr> 
      </table>

      <p><h2>Equipment introduction(設備介紹)</h2></p>

    <table>
        <tr>
          <th>Device</th>
          <th>Device Description</th>
          <th>中文說明</th>
        </tr>

        <tr>
          <td>Gateway</td>
          <td>Used to connect two different types of networks</td>
          <td>用以連接兩個異質性網路</td>
        </tr>

        
        <tr>
            <td>Router</td>
            <td>(1).Used to connect two homogeneous networks<br>(2).Determine the transmission path of IP</td>
            <td>(1).連接兩個同性質網路 <br>((2).決定IP的傳輸路徑</td>
          </tr>

          
        <tr>
            <td>Bridge</td>
            <td>(1) Segments connecting multiple networks.<br>(2) Frame can be filtered to improve network efficiency</td>
            <td>(1)連接多個網路的Segment.<br>(2)可過濾frame，提高網路效率</td>
          </tr>
       
        <tr>
            <td>Repeater</td>
            <td>(1). Signal strength amplification<br>(2). Extend the transmission distance</td>
            <td>(1).訊號強度放大<br>(2).延長傳輸距離</td>
        </tr>
      </table>
    
    <p>資料分布</p>
    <iframe src="https://plotdb.io/v/chart/28209" width="100%" height="600px" allowfullscreen="true" frameborder="0"></iframe>
    <iframe src="https://plotdb.io/v/chart/28210" width="100%" height="600px" allowfullscreen="true" frameborder="0"></iframe>
    <iframe src="https://plotdb.io/v/chart/28211" width="100%" height="600px" allowfullscreen="true" frameborder="0"></iframe>
    

</body>
</html>
