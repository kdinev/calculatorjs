CalculatorJS [![Codacy Badge](https://www.codacy.com/project/badge/20f7e3388f3b49ca8d72a04af2efa622)](https://www.codacy.com/public/kdinev/calculatorjs)[![Build Status](https://travis-ci.org/kdinev/calculatorjs.svg?branch=master)](https://travis-ci.org/kdinev/calculatorjs)
=========

A JavaScript calculator and an expression parser.

Description:

Parses and evaluates mathematical expressions. The expression is provided to the expression parser as a string.

The CalculatorJS is a calculator widget provided dependent on the EpsilonJS expression parser. This widget was created to test the epsilon expression parser. The calculator widget is dependent on jQuery and jQuery UI. In order to use it:
    
    <div id="calculator"></div>
    <script type="text/javascript">
		$(document).ready(function () {
			$("#calculator").calculator();
		});
	</script>

The calculator widget is used in a Windows 8.1 store application which you may download and play with here: [http://apps.microsoft.com/windows/app/epsilon-calculator/ec41ebdd-00c6-4654-a2a2-b297a0118a87](http://apps.microsoft.com/windows/app/epsilon-calculator/ec41ebdd-00c6-4654-a2a2-b297a0118a87)
