Demo
====

.. raw:: html

  <!-- Third Party Libraries -->
  <script type="text/javascript" src="repos/AST-Visualization-on-browser/esprima/esprima.js"></script>
  <script type="text/javascript" src="repos/AST-Visualization-on-browser/raphael-min.js"></script>
  <script type="text/javascript" src="repos/AST-Visualization-on-browser/json2.js"></script>

  <!-- Our code -->
  <script type="text/javascript" src="repos/AST-Visualization-on-browser/ast.js"></script>
  <link rel="stylesheet" type="text/css" href="repos/AST-Visualization-on-browser/style_for_sphinx.css">

   <form id="editor">
    <div id="inputPane">
      <h3>Code Input</h3>
      <textarea name="code" id="codeInput" onkeyup="treeDrawer.parseCode();">
      1 + 2 * 3
      </textarea>
    </div>
    <div id="outputPane">
      <h3>Abstract Syntax Tree as JSON</h3>
      <pre id="json"></pre>
    </div>
  </form>
  <div id="astPane">
    <h3>Abstract Syntax Tree as SVG</h3>
    <div id="ast"></div>
  </div>
