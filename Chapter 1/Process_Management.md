<h3>Main Memory</h3>

<ul>
	<li>Big storage area for 0's and 1's (Bits).</li>
	<li>Where running Kernel and processes reside.</li>
	<li><b>CPU:</b> Reads instructions and data from main memory, and writes back out to memory.</li>
</ul>

<h3>Kernel</h3>

<ul>
	<li><b>Processes:</b> Kernel is responsible for determining which processes are allowed to run on CPU.</li>
	<li><b>Memory:</b> Kernel keeps track of memory, what is allocated to a current process, what is shared, and what is free.</li>
	<li><b>Device Drivers:</b> Kernel acts as an interface between hardware and processes ~ Usually, Kernels job to operate hardware.</li>
	<li><b>System Calls:</b> Processes use them to communicate with Kernel.</li>
</ul>

<h3>Process Management:</h3>
![Image of a Process Management diagram.](https://github.com/HypeByte/My-Linux-Notes/blob/master/Assets/LinuxProcesses.jpg)
<h3>Steps of Process Management:</h3>

<ol>
	<li>Kernel records the state in CPU and memory.</li>
	<li>Kernel Prepares CPU and memory for new process.</li>
	<li>Kernel Tells CPU the <b>time slice</b> for new process</li>
	<li>Switch to <b>User Mode</b> for new process</li>
</ol>

<h3>Process Memory Management</h3>

<ul>
	<li>Kernel needs private area in memory.</li>
	<li>Each User Process needs own section of memory, can share memory, and some is read only.</li>
	<li>Use disk space for extra memory.</li>
	<li>CPU has a MMU (memory management unit) that enables virtual memory.</li>
	<li>MMU uses memory address map to translate memory location from a process into an actual physical memory address.</li>
	<li>Kernel manages the addresses.</li>
	<li>Implementation of memory address map is called page table.</li>
</ul>
      
      
