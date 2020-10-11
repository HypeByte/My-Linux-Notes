<h3>System calls:</h3>

<ul>
    <li>Perform specific tasks that a user process alone cannot do well or at all.</li>
    <li>Two examples are <b>fork()</b> and <b>exec()</b></li>
    <li><b>fork():</b> When a process calls fork(), the kernel creates a nearly identical copy of the process.</li>
    <li><b>exec():</b> When a process calls exec(program), the kernel starts program, replacing the current process.</li>
    <li>All user processes on Linux start as a result of fork() (excluding init), and most of the time, you also run exec() to create a new program.</li>
</ul>


