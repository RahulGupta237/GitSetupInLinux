# GitSetupInLinux


# If your Git password is cached in credential.helper, then unset it:

  git config --local --unset credential.helper
# Or, If you have set your credentials globally, then:

  git config --global --unset credential.helper
# Now go to your GitHub Account settings
   Developer setting
   Personal access token 
   checked marked all box except gist notification delete write
# Now git pull inside your Git repository
    Provide a username and the generated token as a password
    git push origin main 
    Username for 'https://github.com': RahulGupta237
    Password for 'https://RahulGupta237@github.com': copy past generated token
    Enumerating objects: 372, done.
    Counting objects: 100% (372/372), done.
    Delta compression using up to 4 threads
    Compressing objects: 100% (356/356), done.
    Writing objects: 100% (371/371), 30.13 MiB | 4.37 MiB/s, done.
    Total 371 (delta 32), reused 0 (delta 0), pack-reused 0
    remote: Resolving deltas: 100% (32/32), done.
    To https://github.com/RahulGupta237/Courses_Purchase_For_Learning.git
       e229bfa..f4e2cf0  main -> main


