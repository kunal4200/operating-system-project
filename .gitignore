//.pss()system call //
int

pss()
{
struct proc *p;

sti():

acquire(&ptable.lock);

for(p-ptable.proc;p<&ptable.proc(NPROC];p++)
{
if (p->state==SLEEPING)
}
cprintf("%s\t%d WW SLEEPING \n",p->name,p->pid);
}
else if(p->state=RUNNING)
{
cprintf("%s\t\t%d Wit RUNNING In" p->name,p->pid);
}
else if(p->state==RUNNABLE)
{
cprintf("%s %d Wit RUNNABLE in p->name,p->pid);
}
}
//else if(p->state==UNUSED)
//{
//cprintf("%s\t%d\t\t UMUSED \n" name.p->pid):
//}
else if(p->state-EMBRYO)
{
cprintf("%s\t%d W EMBRYO \n" p->name.p->pid);
}
else if (p-->state==ZOMBIE)
{
else if(p->state==ZOMBIE)
}
cprintf("%s \t\t%d\\t\tZOBIE \N",p->name,p->pid);
}
}
release(&ptable.lock);
return 23;
}
