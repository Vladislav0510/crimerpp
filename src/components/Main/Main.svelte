<script>
	import './main.scss'
	import Information from './Information/Information.svelte'
	import Licences from './Licences/Licences.svelte'
	import Skills from './Skills/Skills.svelte'
</script>

<main class='page'>
	<div class='page__main-block main-block'>
		<div class='main-block__body'>

			<Information />
			<div class='progress__row'>
					<Licences />
					<Skills/>
			</div>

		</div>
	</div>


	<div class='page__image _ibg'>
		<img src='images/BG.jpg' alt='background'>
	</div>

	<!--	возможно мои компоненты нужно обвернуть в блок для картинки-->


</main>