# Repo-A-B
.create repo A
.create repo B
.create unified repo A-B
.set repos A and B as submoules for repo A-B (git submodule add 'repo URL' repo name)
.two folders repo A and repo B appear under repo A-B 
.commite and push changes in the seperated folders of repo A and repo B
.update submodules in repo A-B (git submodule update --remote repo Name)
.use (git 'command' -- recursive) => to make git command include submodules 
.after adding confi.yaml submodule repo-A in repo-A-B can access it but it cannot be access in the seperated repo-A
.thought about access yaml file from repo using yaml url (did not work for me)
