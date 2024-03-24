# Live Coding / BP Corruption
> This info is based on what people told me.
### Related to:
* In cases when Details/Hierarchy have nothing in them
* When C++ Variables on usage contain `nullptr`.

### In `Live Coding` settings those are main two BP corrupting fellas:
* Enable Reinstancing.
* Automatically Compile Newly Added C++ Classes.

### Solutions:
* Reparenting the BP.
* Deleting corrupted components from C++, compiling, and then adding then and recompiling again.
------------------------

# Nodes might contain additional info that they might not show
> This info is based on my personal experience.
* In case of default Gameplay Tags: Nodes might show not what it actually contains. 

### Causes:
* Renaming of the Tags seems to cause something like this.

### Solutions:
* In Such case you need to simply recreate the node.[Useful Resources.md](Useful%20Resources.md)