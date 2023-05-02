Download Link: https://assignmentchef.com/product/solved-cpe434-homework-6
<br>
<ol>

 <li><strong><u> </u>Multi-level page tables</strong>. Assume a virtual address machine with a 32bit address. Assume the address is divided into 4 parts a,b,c,d with the first three parts used to index into a three level page table and the fourth is used to index into the location on the page. Assume the values for a,b,c,d are 4,6,6,16 respectively resulting in a 64 KB  sized page</li>

</ol>

<ul>

 <li>what is the total size in bytes of the page tables for the smallest program, which is a program containing a single page of  text and heap, starting at location 0, and a separate  page for the stack, starting at location 0xFFFFFFFF and running downwards.  Assume all page table entries are 4 byes each.</li>

 <li>what is the total size in bytes of the page tables for the largest program, which is a program containing text, heap and stack which fill the entire 32bit address space.</li>

 <li>which page table entries are used to access address 0xffff0000</li>

</ul>

<ol start="2">

 <li><strong><u> </u>Inverted Page tables</strong>. Assume a virtual address machine with a 64 bit address. Assume a page is 64K bytes long, indexed by the lowest 16 bits.  Assume the system used inverted page tables because of the large size of the address.</li>

</ol>

<ul>

 <li>How many bits of the address are used to hash into the inverted page table</li>

 <li>Assume the machine has 16 GB of memory available.  How big is the inverted page table size, in bytes, assuming each entry is 128  bits which includes 64 address bits and 64 control bits Do not include any linked lists that might be necessary for resolving collisions.</li>

 <li>how many bits of the address are used for the comparison operation used to disambiguate addresses that map into the same page table entry..</li>

 <li>What is the maximum number of virtual pages that might be mapped into the first page table entry. Explain your answer.</li>

</ul>

<ol start="3">

 <li><strong><u></u> Posix</strong> <strong>Shared Memor</strong></li>

</ol>

<ul>

 <li>points – Should posix shared memory be cachable or non-cachable. Explain your answer.</li>

</ul>

<ul>

 <li>When three programs share a block of memory, when is the memory returned to the system</li>

</ul>

<strong>   </strong>when the first program exits

when the last program exits

when returned explicitly by a program

when the system reboots.




<ul>

 <li>Can we create a linked list in shared memory that is shared between two processes and if so what are the constraints, if any?</li>

</ul>