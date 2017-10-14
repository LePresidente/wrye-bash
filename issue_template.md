Please see [here](https://github.com/wrye-bash/wrye-bash/wiki/[github]-Reporting-a-bug)
for guidelines on reporting issues. In particular, you must provide the info/steps below:

### Link to the forum thread you reported the issue

**IMPORTANT**: Before posting an issue, be sure to ask at the official threads:
[AFK mods](https://afkmods.iguanadons.net/index.php?/topic/4966-wrye-bash-all-games/&do=getNewComment)
(or [Bethesda](https://bethesda.net/community/topic/38798/relz-wrye-bash-oblivion-skyrim-skyrim-se-fallout-4/) )
**POST AN ISSUE ON GITHUB _ONLY_ AFTER DOING SO**.

Add the link to your post here:

### Try the latest nightly build:

Download from the [second post in AFK mods thread](https://afkmods.iguanadons.net/index.php?/topic/4966-wrye-bash-all-games/&do=findComment&comment=166863)

### Info on your installation

* You must produce a bashbugdump.log and include its contents in the codebox below

    ```
    Contents of the bashbugdump
    ```

    See [here](https://github.com/wrye-bash/wrye-bash/wiki/[github]-Reporting-a-bug#the-bashbugdumplog)
for generating the bugdump

* **Your operating system!** If on Windows Vista or later and the game is in
the default directory (ex: *C:\Program Files (x86)\Bethesda Softworks\Oblivion*),
please install it somewhere else (like *C:\Games\Oblivion*). This can cause
lots of problems, due to UAC (User Account Control).

* **Wrye Bash version!** _Also_ specify if you are using Python Wrye Bash, or
Standalone Wrye Bash exe ( WBSA ). If you're using a development version, be
sure to include the *commit SHA*.

#### Are you using a **bash.ini** ?

* If so, include its contents in the codebox below, or if too big attach it to this issue

    ```
    Contents of the bash.ini
    ```

### Info on the bug

* **Bug description** - be sure to include:
  * what you did (_**step-by-step**_),
  * what you expected, and
  * what happened.

  If your problem is related to a particular mod, link us to it adding the
  exact version we should download
* Any and every **error message** you encounter - post at least the contents
of any `stdout/stderr` window that pops up with errors (python tracebacks).

* Is the problem related to the **Bashed Patch** ? If so include the following:
  * Your Load Order (attach a txt). Right click on a column header in the Mods tab > 'List Mods...'.
  * Your Bashed Tags (attach a txt). Right click on a column header in the Mods tab > 'List Bash Tags...'.
  * Your Bashed Patch config (attach a txt). Right click on the Bashed patch in the Mods tab > 'List Patch Config...'.

  Be sure to supply the **minimal load order and patch options that reproduce
  your bug.** That is, deselect all batch patch options and deactivate all the
  mods, then try to pin down which options and which mods trigger the bug.
