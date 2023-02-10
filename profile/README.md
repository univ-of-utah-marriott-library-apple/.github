# University of Utah - Marriott Library - Apple Infrastructure
<img src="marriott_lib_building.png">

### Notable Repositories

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=univ-of-utah-marriott-library-apple&repo=python-jamf&show_icons=true&theme=swift)](https://github.com/univ-of-utah-marriott-library-apple/python-jamf)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=univ-of-utah-marriott-library-apple&repo=jctl&show_icons=true&theme=swift)](https://github.com/univ-of-utah-marriott-library-apple/jctl)

### Links & Resources

#### :teacher: [2023 Jan - Univ of Utah MacAdmins - jctl – Jamf Pro Efficiency & Automation](https://stream.lib.utah.edu/index.php?c=details&id=13542)
> `jctl` is a command line tool that allows you to read, create, edit, and delete Jamf Pro data. `python-jamf` is the Python library that powers jctl. `python-jamf` interacts with Jamf Pro’s Classic API and hides all the details and complexity of retrieving, modifying, and uploading the Classic API data. Some people still use curl and shell CLI tools to parse and modify the raw Jamf Pro data. `python-jamf` converts all the data to Python dictionaries and arrays, so only a little bit of Python knowledge makes it extremely easy to do far more than curl and the shell can do like mass modify records and cross-reference records. For example, once the preferences are configured, `import jamf` and then `jamf.Computers()` will give you an object that contains all the computers on your server. You can get an array of computers with a specific name with ` jamf.Computers().recordsWithName("mac")`. Once you pick a computer, you can change some data by simply writing `computer.data['general']['name'] = "old mac"` and then saving it `computer.save()`. It’s really that easy. This is made abundantly clear by the pkgctl tool, which was written very quickly, has only about 550 lines of code, and interactively goes through all of the packages stored in Jamf and allows you to “promote” packages, that is, swap one package for another in policies, patch management, and computer group criteria. Half of the `pkgctl` code is the interactive print and input statements. You can do a tremendous amount with very little code. In this presentation, James will demo `jctl`, `pkgctl`, and a little bit of Python code showing how easy they are to use.

#### :teacher: [JNUC 2021 - Turn 1000 clicks into 1 with python-jamf and jctl (YouTube)](https://youtu.be/2YLriNwyP3s)
> The `jctl` command line tool interacts with Jamf Pro or Jamf Cloud and allows the administrator perform repetitive tasks quickly and easily. The `python-jamf` library simplifies interacting with the Classic API and powers `jctl`.  This session will introduce [python-jamf](https://github.com/univ-of-utah-marriott-library-apple/python-jamf) and [jctl](https://github.com/univ-of-utah-marriott-library-apple/jctl), give some usage examples, show how it works internally, and show how easy it is to add your own functionality to perform and automate any repetitive and complex task you want.

#### :question: [`jctl` - MacAdmins Slack Channel](https://macadmins.slack.com/archives/C01C8KVV2UD)
> If you have additional questions, or need more help getting started, post a question on the MacAdmin's Slack [#jctl](https://macadmins.slack.com/archives/C01C8KVV2UD) channel.

#### :technologist: [University of Utah -  MacAdmins Blog](https://apple.lib.utah.edu)
> The University of Utah, MacAdmins Meeting is held monthly virtually on the 3rd Wednesday of each month at 11 AM Mountain Time. Presentations cover Apple technology and integration in a heterogeneous university enterprise environment. For latest meeting agenda & other posts, checkout & follow our [campus MacAdmin blog](https://apple.lib.utah.edu).

#### :vhs: [University of Utah - MacAdmins Archived Presentations](https://stream.lib.utah.edu/index.php?c=browse&m=results&q=%22mac+manager%22&cat=&sort=newest)

> To view and accessed 20+ years of archived University of Utah, [MacAdmins presentations and slides](https://stream.lib.utah.edu/index.php?c=browse&m=results&q=%22mac+manager%22&cat=&sort=newest).
