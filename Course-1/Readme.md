<h3>Introduction to Front end developement</h3>
<div id="topic1">
  <h4>Topic-1</h4>
  <h5>Working with IP(Internet Protocols)</h5>
  <p>
    <ul>
      <li>Just like we send mails via post, <em>computers send data via IP or Internet Protocol.</em></li>
      <li>Every single computer in a network has an IP address just like the address mentioned on the mail that we intend to send via post.</li>
    </ul>
    There are 2 latest version of IP that are widely used.
    <ol>
      <li>IPv4</li>
      <p>This has an <em>octet seperated by "."</em>. For eg: 192.0.0.235</p>
      <li>IPv6</li>
      <p>This contains <em>hexadecimal digits seperated by a colon</em>.</p>
      <img src="https://user-images.githubusercontent.com/54028832/214232184-e3feffeb-f16f-4ec7-9167-6275bce21aae.png" alt=ipv6 align="center" />
      <h5>Image Source: Wikipedia</h5>
    </ol>
</div>
<div id="topic2">
  <h5>IP Packets</h5>
  <p>When the data is sent from the server to the device, that data is called as IP packet also known as data gram.</p>
  <h6>High level overview of IP packet</h6>
  <img src="ip packet.png" alt="ip packet" width=50%/>
  <h5> Problems with IP packets</h5>
  <h6><p><ol>
    <li>They may be damaged or corrupt during transit.</li>
    <li>Might arrive out of order.</li>
    <li>Dropped or lost during transit.</li>
    </ol></p></h6>
   <h5>How to overcome these problems?</h5>
   <h6>
    <p>There are other protocols that solve these problems. The payload part of the IP packet has many other protocols.
    The most common protocols are:
    <ol>
      <li>TCP <em>(Transmission Control Protocol)</em>:
        <p>TCP solves all the 3 above mentioned problems with a small delay. This protocol is used for sending data correctly and in order such as text or an image.</p>
      </li>
      <li>UDP <em>(User Datagram Protocol)</em>:
        <p>UDP on the other hand solves the corrupt packet issue. However, IP packet can arrive out of order. In simple terms, this protocol is used for sending that data which can have some data loss such as a video stream, phone call.</p>
      </li>
    </ol>
    The fun part is that these protocols contain payload which further has other protocols.
    </p>
   </h6>
  <h6>The HTTP protocol</h6>
  <h6><p>
  A few pointers about HTTP:
  <ul>
    <li>It is a <em>Communication</em> Protocol.</li>
    <li>It is responsible for tranferring the html files, images, and other types of files.</li>
    <li>It is a request-response based protocol.</li>
    <li>HTTP Methods:
      <ul><li> GET-> Retrieve data server.</li>
      <li> POST-> Send data to the server. </li>
      <li>PUT-> Update any info currently on the webserver with something else.</li>
      <li>DELETE-> Removes the resource.</li></ul>
    </li>
  </ul></p></h6>
  <h5>Make up of a HTTP request</h5>
  <h6>
  <p>Eg of a HTTP response:</p>
  
  

  </h6>
</div>
