

    1. /home/kashwikavelanati


   2. ls -a displays hidden directories and files (like .bashrc or .cache) that standard directory listings hide. The -a flag represents "all," targeting anything starting with a leading dot (.).


   3. Inside the listing drwxr-xr-x 2 kashwikavelanati kashwikavelanati 4096 Aug 25 17:10 Downloads, the string at the start represents type and access rights:
   * d: Specifies that the entry is a directory.
      * r: Grants read permissions.
      * w: Grants write permissions.
      * x: Grants execute permissions.


   4. The path coding-cafe/week02 works safely because it is formatted as a relative path. It processes starting from the current directory context (home) instead of anchoring to the root (/).


   5. The mv utility was executed to transfer a file across directories and subsequently alter its filename inside that destination.


   6. The active system environment configuration contains 9 folders mapped onto its PATH.


   7. /usr/bin/python3


   8. No, they are distinct. Each computer environment sets up custom PATH configurations, causing their Python framework installation destinations to vary.


   9. The operating system prompt displayed Command 'python3' not found because the shell scanned every directory configured under the environment's PATH variables but failed to locate the matching binary executable.


  

   10. cd .. shifts your current terminal location up by exactly one level in the system structure, moving you directly into the parent directory.


   11. The entry . represents the directory you are currently working in, whereas .. references the immediate parent directory one level above.


   12. Running cd with no trailing arguments automatically redirects the command line session back to your primary user home directory.


   13. The structural notation ~ acts as a shortcut token pointing directly to your primary user directory.


   14. Entering cd ~/coding-cafe/week02 works seamlessly because it relies on an absolute path definition from the root user space, enabling execution regardless of which folder the user currently occupies.


   15. Executing cd coding-cafe/week02 from inside the /home folder errors out because it expects the path to exist within /home itself. Because the actual path resides one level deeper inside /home/kashwikavelanati, the subfolder cannot be resolved.


   16. The echo $PATH command evaluates and displays the environment variable contents to output all search directories as a colon-separated list.

