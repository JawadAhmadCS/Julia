# Setting Up Julia for Jupyter Notebook

### Step 1: Download and Install Julia  
First, go to [Julia's official website](https://julialang.org/downloads/) and download the latest version. After downloading, install it following the default setup.  

To install [old version](https://julialang.org/downloads/oldreleases/)

Make sure old version will be uninstalled even `.julia` folder from `C:\Users\mjawa\.julia` and other all folders.

### Step 2: Open Julia App  
Once installed,run julia application. You can do this by running `C:\Julia-1.11.3\bin\julia.exe` You should see a screen similar to this:  

![image](https://github.com/user-attachments/assets/4775ef0d-a6b4-4ab3-a8dd-d7a9da7b4df6)



### Step 3: Install IJulia  
In the Julia REPL, run the following commands:  
```julia
import Pkg
Pkg.add("IJulia")
```
This will automatically install IJulia for Jupyter Notebook.

### Rebuild the Package:
If there's a specific error, you can try rebuilding your environment:

```
using Pkg
Pkg.build("IJulia")
```
### Step 4: Verify Installation
To check if everything is set up correctly, open Jupyter Notebook and see if the Julia kernel is available than its ok.


For more detail:[ see this](https://youtu.be/oyx8M1yoboY)
