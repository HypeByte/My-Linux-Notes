<h3>Levels/Layers:</h3>
  <ul>
    <li><b>Layers:</b> Groups components based on how close they are to hardware.</li>
    <li><b>Linux Main Three Layers:</b> Computer hardware, Kernel, User Processes.</li>
    <li><b>User Space:</b>Running programs the kernel manages.</li>
  </ul>
  
  <table>
    <thead>
      <tr>
        <th>User Processes</th>
        <th>Kernel</th>
        <th>Hardware</th>
      </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <ul>
          <li>Games</li>
          <li>Shell</li>
          <li>Server</li>
        </ul>
      </td>
       <td>
         <ul>
           <li>System Calls</li>
           <li>Process Management</li>
           <li>Memory Management</li>
           <li>Device Drivers</li>
          <ul>
            </td>
        <td>
          <ul>
            <li>CPU</li>
            <li>RAM</li>
            <li>Disks</li>
            <li>Network Ports</li>
          </ul>
           </td>
    </tr>
  </tbody>
  </table>
   
  <b>User Processes ---> User Mode</b>
  <br></br>
  <b>Kernel ---> Kernel Mode</b>
  
  <table>
   <thead>
     <tr>
     <th><b>Kernel Mode</b></tr>
     <th><b>User Mode</b></tr>
    </tr>
  </thead>
  <tbody>
    <td>
      <ul>
        <li>Access to CPU and Main Memory.</li>
        <li><b>Kernel Space:</b> Area only Kernel can use.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Restricts access to subset of memory and CPU operations.</li>
        <li><b>User Space:</b> Parts of main memory that user processes can access.</li>
      </ul>
    </td>
    </tdbody>
    </table>
          
  
  
