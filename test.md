<a href="vscode://file/D:/Workbench/Projects/Coding/Toolkit-and-Snippets">Open My Project in VS Code</a>


[Open Toolkit-and-Snippets in VS Code](vscode://file/D:/Workbench/Projects/Coding/Toolkit-and-Snippets)


<button onclick="copyVSCodeLink()">Copy</button>

<script>
function copyVSCodeLink() {
  const link = "vscode://file/D:/Workbench/Projects/Coding/Toolkit-and-Snippets";
  navigator.clipboard.writeText(link).then(() => {
    alert("Copied to clipboard:\n" + link);
  }).catch(err => {
    alert("Failed to copy: " + err);
  });
}
</script>