# Coldfire
A self-replicating internet worm written in assembly

**Implementation ideas:**

- ring0 advances through kernel32.dll and other funny APIs
- stick itself into the CurrentVersion/Run registry for autostartup
- encrypt itself by using polymorphic engine
- make funny filenames by giving 128bit polymorphic mutex names
- melt the source files or give the tag 'hidden'
