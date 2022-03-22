<?php  
	session_start();
	if (!isset($_SESSION['nombre'])) {
		header('Location: login.php');
        
	}elseif(isset($_SESSION['nombre'])){
		include 'model/conexion.php';
		$sentencia = $bd->query("SELECT * FROM alumno;");
		$alumnos = $sentencia->fetchAll(PDO::FETCH_OBJ);
		//print_r($alumnos);
	}else{
		echo "Error en el sistema";
	}


	
?>

<!DOCTYPE html>
<html lang="es">
<head>
	<title>Lista de alumnos</title>
	<meta charset="utf-8">
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
</head>
<body>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

<div class="container">
  <div class="row">
    <div class="col">
	<center>
		<h1>Bienvenido: <?php echo $_SESSION['nombre'] ?></h1>
		<a href="cerrar.php">Cerrar Sesión</a>
		<h3>Lista de Alumnos</h3>
		<table class="table table-dark table-hover">
			<tr>
				<td>Código</td>
				<td>Apellido paterno</td>
				<td>Apellido materno</td>
				<td>Nombre</td>
				<td>Parcial</td>
				<td>Final</td>
				<td>Promedio</td>
				<td>Editar</td>
				<td>Eliminar</td>
			</tr>

			<?php 
				foreach ($alumnos as $dato) {
					?>
					<tr>
						<td><?php echo $dato->id_alumno; ?></td>
						<td><?php echo $dato->ap_paterno; ?></td>
						<td><?php echo $dato->ap_materno; ?></td>
						<td><?php echo $dato->nombre; ?></td>
						<td><?php echo $dato->ex_parcial; ?></td>
						<td><?php echo $dato->ex_final; ?></td>
						<td><?php echo ($dato->ex_final + $dato->ex_parcial)/2; ?></td>
						<td><a href="editar.php?id=<?php echo $dato->id_alumno; ?>" class="btn btn-primary">Editar</a></td>
						<td><a class="btn btn-danger" href="eliminar.php?id=<?php echo $dato->id_alumno; ?>">Eliminar</a></td>
					</tr>
					<?php
				}
			?>
			
		</table>

		<!-- inicio insert -->
		<hr>
		<h3>Ingresar alumnos:</h3>
		<form  class="table table-dark table-hover" method="POST" action="insertar.php">
			<table>
				<tr>
					<td>Apellido paterno: </td>
					<td><input type="text" name="txtPaterno"></td>
				</tr>
				<tr>
					<td>Apellido materno: </td>
					<td><input type="text" name="txtMaterno"></td>
				</tr>
				<tr>
					<td>Nombre: </td>
					<td><input type="text" name="txtNombre"></td>
				</tr>
				<tr>
					<td>Nota parcial: </td>
					<td><input type="text" name="txtParcial"></td>
				</tr>
				<tr>
					<td>Nota final: </td>
					<td><input type="text" name="txtFinal"></td>
				</tr>
				<input type="hidden" name="oculto" value="1">
				<tr>
					<td><input type="reset" name="" class="btn btn-dark"></td>
					<td><input type="submit" value="Aceptar" class="btn btn-dark"></td>
				</tr>
			</table>
		</form>
		
		
		
		
		
		
		
		
		
    
    
    
		<!-- fin insert-->

	</center>
	 </div>
  </div>
</div>
	
</body>
</html>