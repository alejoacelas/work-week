# Work week

A page that shows what a person's working week consists of, task by task: what each
task is, how long it took, which software it touched, whether the work there was
done by hand or by an AI assistant, and whether the task is written down anywhere.

An AI assistant gathers the tasks from the person's own records, puts them as JSON
into the `baked` script tag of `index.html`, and hands back the file. Nothing is
sent anywhere: the page is a single file with no network requests.

Keys: `↑` `↓` move between tasks, `←` `→` between days, `W` shows the week, `E`
shows the evidence behind a task. The address updates with the selected day and
task, so a link reopens the same view.
