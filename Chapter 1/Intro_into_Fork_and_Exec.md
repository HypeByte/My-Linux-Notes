<h3>System calls:</h3>

<ul>
    <li>Perform specific tasks that a user process alone cannot do well or at all.</li>
    <li>Two examples are <b>fork()</b> and <b>exec()</b></li>
</ul>

<p><b>fork():</b> When a process calls fork(), the kernel creates a nearly identical copy of the process.</p>
<p><b>exec():</b> When a process calls exec(program), the kernel starts program, replacing the current process.</b>
