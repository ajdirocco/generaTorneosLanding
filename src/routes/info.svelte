<script>
	import { fade } from 'svelte/transition'
</script>

<svelte:head>
	<title>Info</title>
</svelte:head>

<div class=" bg-white" transition:fade>
	<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
	  <div class="lg:text-center">
		<p class="mt-0 text-3xl leading-8 font-extrabold tracking-tight text-indigo-500 sm:text-4xl text-center">
		  Crea tus torneos
		</p>
		<p class="mt-4 max-w-2xl text-xl text-gray-500 lg:mx-auto text-center">
		  Con un click genera toda la info. Edita lo que veas entre rayitas.
		</p>
	  </div>

	  <div class="mt-5 md:mt-0 md:pr-12 md:py-8 mb-8 pb-10 border-b border-gray-200">
		<dl
		  class="space-y-5 md:space-y-1 md:grid md:grid-cols-2 md:gap-x-8 md:gap-y-10"
		>
 		  <div class="flex">
			<div class="ml-4">
			  <dt class="text-lg leading-6 font-medium text-gray-900">
				💲 Precio
			  </dt>
			  <dd class="mt-2 text-base text-gray-500 text-justify">
				Esta versión es <b>gratuita</b>. Eventualmente se desarrollarán nuevas versiones con algún tipo subscripcón.
			  </dd>
			</div>
		  </div>

		  <div class="flex">
			<div class="ml-4">
			  <dt class="text-lg leading-6 font-medium text-gray-900">
				📧 Conctacto
			  </dt>
			  <dd class="mt-2 text-base text-gray-500 text-justify">
				<b>generatorneos@gamil.com</b>.
				Contestaremos tu inquietud lo mas pronto posible.
			  </dd>
			</div>
		  </div>
		  <div class="flex">
			<div class="ml-4">
			  <dt class="text-lg leading-6 font-medium text-gray-900">
				🏆 Versión actual
			  </dt>
			  <dd class="mt-2 text-base text-gray-500 text-justify">
				Se generan dos tipos de torneo: <b>Campeonato</b> (round-robin) y <b>Copa</b> (grupos y llaves). Todo torneo se graba localmente en el dispositivo y puede ser compartido a través de la opción Exportar.
			  </dd>
			</div>
		  </div>
		  <div class="flex">
			<div class="ml-4">
			  <dt class="text-lg leading-6 font-medium text-gray-900">
				😀 Apps
			  </dt>
			  <dd class="mt-2 text-base text-gray-500 text-justify">
				Quizas te interesen estas otras aplicaciones:
			  </dd>
			  	<a href="https://generapaplicaciones.netlify.app/"
			  		class="mt-4 inline-flex items-center py-1 text-indigo-700  hover:text-indigo-900  text-base md:mt-0 cursor-pointer focus:outline-none focus:border-none"
			  		rel="noopener noreferrer"
			  		target="_blank">
			  		Genera Aplicaciones.
		  		</a>
			</div>
		  </div>
<!--
		  <div class="flex">
			<div class="ml-4">
			  <dt class="text-lg leading-6 font-medium text-gray-900">
				🔖 Próximas versiones
			  </dt>
			  <dd class="mt-2 text-base text-gray-500 text-justify">
				Podrás
				<b>compartir la edición</b> con otros usuarios y acceder a los torneos desde <b>todos tus dispositivos</b>.
			  </dd>
			</div>
		  </div> -->
		</dl>
	  </div>
	</div>
</div>

