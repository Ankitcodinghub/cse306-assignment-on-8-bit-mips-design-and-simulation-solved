# cse306-assignment-on-8-bit-mips-design-and-simulation-solved
**TO GET THIS SOLUTION VISIT:** [CSE306 Assignment on 8-bit MIPS Design and Simulation Solved](https://www.ankitcodinghub.com/product/cse306-assignment-on-8-bit-mips-design-and-simulation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95168&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE306&nbsp;Assignment on 8-bit MIPS Design and Simulation Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
CSE306

Assignment on 8-bit MIPS Design and Simulation

1 DESIGN SPECIFICATION

<ul>
<li>TherewillbeamultiplexedAddressandDatabuswith8-bitswidth.</li>
<li>BothDataandaddresswillbeof8-bits.</li>
<li>Youhavetouse/implement8-bitALU,hencethename8-bitMIPS.</li>
<li>Youmusthavetodesignthefollowingtemporaryregisters:
$zero, $t0, $t1, $t2, $t3, $t4

All these registers will be of 8-bits and the assembly code that will be provided to simu- late your design will use only these mentioned registers.
</li>
<li>The Control unit should be microprogrammed. The control signals associated with the operations should be stored in a special memory (you can use a separate ROM for this purpose) units as Control Words.</li>
<li>During the simulation, as Assembly Code will be given and you have to convert it into your designed MIPS machine code. The conversion process should be automatic. For example, you can write code in your preferred programming language for this conver- sion.</li>
<li>Markswillvaryaccordingtotheefficiencyofdesign.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2 INSTRUCTION SET DESCRIPTION

</div>
</div>
<div class="layoutArea">
<div class="column">
Instruction ID

A B C D E F G H I J K L M N O P

</div>
<div class="column">
Instruction Type

</div>
<div class="column">
Instruction

</div>
</div>
<div class="layoutArea">
<div class="column">
Arithmetic add Arithmetic addi Arithmetic sub Arithmetic subi

Logic and Logic andi Logic or Logic ori Logic sll Logic srl Logic nor

Memory sw Memory lw

Control beq Control bneq Control j

</div>
</div>
<div class="layoutArea">
<div class="column">
3 MIPS INSTRUCTION FORMAT

Our MIPS Instructions will be 20-bits long with the following three formats.

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>R-type</li>
<li>I-type</li>
<li>J-type</li>
</ul>
</div>
<div class="column">
Opcode 4-bits

Opcode 4-bits

Opcode 4-bits

</div>
<div class="column">
Src Reg 1 4-bits

Src Reg 1 4-bits

</div>
<div class="column">
Src Reg 2 4-bits

Src Reg 2 4-bits

</div>
<div class="column">
Dst Reg Shft Amnt 4-bits 4-bits

Address / Immediate 8-bits

0 0 4-bits 4-bits

</div>
</div>
<div class="layoutArea">
<div class="column">
Target Jump Address 8-bits

</div>
</div>
<div class="layoutArea">
<div class="column">
4 MEMORY CONSIDERATIONS

</div>
</div>
<div class="layoutArea">
<div class="column">
You need to consider three types of memory:

• InstructionMemory(accessedthroughprogramcounter,pc) • DataMemory(accessedthroughaddress)

• StackMemory(accessedthroughstackpointer,spSampleinstruction:sw$t0,0($sp)or lw $t1, 4($sp))

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
5 INSTRUCTION SET ASSIGNMENT

The opcodes of the instruction will be between 0 to 15 based on the sequence of instruction id given below. Sequence ABCDEFGHIJKLMNOP means add instruction’s opcode will be 0, addi instruction’s opcode will be 1, sub instruction’s opcode will be 2, and so on.

</div>
</div>
<div class="layoutArea">
<div class="column">
Group ID

1 2 3 4 5 6

</div>
</div>
<div class="layoutArea">
<div class="column">
Section A1 Section A2 Section B1 Section B2

LEJBHKFIGACONMPD AGOJPKFNCIMBLEHD GDOMBACPKFLENHJI AEHKFCIJLODNPBMG MPNGOKCJILFDBEAH JFMGKLNEPBCHDAIO DCJOGPAFBINHEKLM MPOEGBJAKHCILNFD OFLAJDBCEKIMNHPG HCNJKAGMBDEFPIOL EFLAIDPKCHOBNGMJ MDHKCPOALIENBGFJ FELDBNJKAIOHMGPC NFPKOLAJEIBHGMCD PGMAJLBFHNCKOEDI PJDKHOBAGNCFLIME HGIADLKMJBFECOPN CKPIBEJHDLFMGANO PEJHODFLNAKGBIMC MBJNKEFOGDHCALPI IDFGJMLHOKNCBEAP GOCFJDBLEMIAHPNK PNDBCAMLHIJOKEGF CDEFGMBOAJHIKPLN

6 REPORT CONTENT

Contents of the report are recommended as follows:

<ul>
<li>Introduction</li>
<li>InstructionSet</li>
<li>CircuitDiagramprintedindrawingpaper(Willdiscussaboutthispointintheclass)</li>
<li>Howtowriteandexecuteaprograminthismachine</li>
<li>SpecialFeaturesImplementedifany(maycarrybonusmarks)</li>
<li>ICsusedwiththeircount</li>
<li>Discussion</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
