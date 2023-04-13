<html lang="es">
	<head>
		<title>ColorPik</title>
	</head>
	<body>
		<div class="container">
			<div class="header">
				<img class="logo" src="/images/logo_transparent.png" alt="Logo de ColorPik" />
			</div>
			<main>
				<slot />
			</main>

			<footer>
				<div class="columna">a</div>
				<div class="columna">a</div>
				<div class="columna">a</div>
			</footer>
		</div>
	</body>
</html>

<style>
	html,
	body {
		margin: 0;
		padding: 0;
		height: 100%;
	}

	.container {
		min-height: 100%;
		display: flex;
		flex-direction: column;
	}

	footer {
		background-color: #333333;
		color: #dfdde4;
	}

	.header {
		display: flex;
		justify-content: center;
		align-items: center;
		text-align: center;
	}

	main {
		flex: 1;
	}

	footer {
		height: 10%;
		display: flex;
		flex-direction: row;
		justify-content: space-between;
		text-align: center;
		margin-top: auto;
	}

	.columna {
		flex: 1;
		/* Otros estilos para las columnas */
	}

	.logo {
		max-height: 15vh;
		max-width: 100%;
	}
</style>
