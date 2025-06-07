<!DOCTYPE html>
<html>
<head>
  <title>Graph Equation</title>
  <script src="https://cdn.plot.ly/plotly-latest.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjs/11.11.0/math.js"></script>
</head>
<body>
  <h2>Graph Your Equation</h2>
  <input type="text" id="equation" placeholder="Enter equation like x^2 + 2*x" />
  <button onclick="plotGraph()">Plot</button>

  <div id="plot" style="width: 100%; height: 500px;"></div>

  <script>
    function plotGraph() {
      const expr = document.getElementById("equation").value;
      const xValues = [];
      const yValues = [];

      for (let x = -10; x <= 10; x += 0.1) {
        try {
          const scope = { x };
          const y = math.evaluate(expr, scope);
          xValues.push(x);
          yValues.push(y);
        } catch (e) {
          alert("Invalid equation");
          return;
        }
      }

      const trace = {
        x: xValues,
        y: yValues,
        mode: "lines",
        type: "scatter"
      };

      Plotly.newPlot("plot", [trace]);
    }
  </script>
</body>
</html>
