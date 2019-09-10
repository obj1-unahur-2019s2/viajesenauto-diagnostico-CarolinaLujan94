//clientes
 
object ludmila {
	method valorPorKm() { return 18 } }

object anaMaria {
	var property esEstable = true
	method valorPorKm() { 
		if (esEstable) return 30
      else  return 25 } }


object teresa {
	var property valorPorKm = 22 }

object melina {
	var property cliente
	method valorPorKm() = cliente.valorPorKm - 3 }
	
	
//remiseras
	
	object roxana {
    method valorPorViaje(cliente, km) = cliente.valorPorKm() * km }

object gabriela {
    method valorPorViaje(cliente, km) = cliente.valorPorKm * 1.2 } 

object mariela {
	method valorPorViaje(cliente, km) = 50.max(cliente.valorPorKm() * km) }

object juana {
	method valorPorViaje(cliente, km) { 
		if (km > 8) return 100
		else return 200
		} 
}

object lucia {
	var property reemplaza
	method valorPorViaje(cliente, km) = reemplaza.valorPorViaje(cliente, km) }