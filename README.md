# massrename
Rename multiple files in a directory based on patterns/options.

Syntax:

  massrename [-r] [-u] [-p <pattern>] [-l] [-g] [-f <pattern>] [-t <pattern>]

-r: Really run. This thing defaults to dry-run since wrongly renaming 150 files sucks. Trust me.
-u: Remove underscores and uppercase first letter. For some reason.
-p: Prepend <pattern> to filenames.
-l: Lowercase filenames.
-g: When -f and -t are specified, makes replacement global.
-f: Replace from <pattern>
-t: To <pattern>

