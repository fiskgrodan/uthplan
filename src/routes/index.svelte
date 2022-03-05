<script context="module">
	export const prerender = true;
</script>

<svelte:head>
	<title>Uthplan</title>
</svelte:head>

<main>
	<section class="realm">
		<div class="heading albion">Albion</div>
		<div class="base">Fighter</div>
		<div class="class"><a href="/armsman">Armsman</a></div>
		<div class="class"><a href="/paladin">Paladin</a></div>
		<div class="class"><a href="/mercenary">Mercenary</a></div>
		<div class="class"><a href="/reaver">Reaver</a></div>
		<div class="base">Acolyte</div>
		<div class="class"><a href="/cleric">Cleric</a></div>
		<div class="class"><a href="/friar">Friar</a></div>
		<div class="base">Rogue</div>
		<div class="class"><a href="/infiltrator">Infiltrator</a></div>
		<div class="class"><a href="/minstrel">Minstrel</a></div>
		<div class="class"><a href="/scout">Scout</a></div>
		<div class="base">Mage</div>
		<div class="class"><a href="/cabalist">Cabalist</a></div>
		<div class="class"><a href="/sorcerer">Sorcerer</a></div>
		<div class="base">Elementalist</div>
		<div class="class"><a href="/theurgist">Theurgist</a></div>
		<div class="class"><a href="/wizard">Wizard</a></div>
		<div class="base">Disciple</div>
		<div class="class"><a href="/necromancer">Necromancer</a></div>
	</section>
	<section class="realm">
		<div class="heading hibernia">Hibernia</div>
		<div class="base">Naturalist</div>
		<div class="class"><a href="/bard">Bard</a></div>
		<div class="class"><a href="/druid">Druid</a></div>
		<div class="class"><a href="/warden">Warden</a></div>
		<div class="base">Guardian</div>
		<div class="class"><a href="/blademaster">Blademaster</a></div>
		<div class="class"><a href="/hero">Hero</a></div>
		<div class="class"><a href="/champion">Champion</a></div>
		<div class="base">Magician</div>
		<div class="class"><a href="/eldritch">Eldritch</a></div>
		<div class="class"><a href="/enchanter">Enchanter</a></div>
		<div class="class"><a href="/mentalist">Mentalist</a></div>
		<div class="base">Stalker</div>
		<div class="class"><a href="/nightshade">Nightshade</a></div>
		<div class="class"><a href="/ranger">Ranger</a></div>
		<div class="base">Forester</div>
		<div class="class"><a href="/animist">Animist</a></div>
		<div class="class"><a href="/valewalker">Valewalker</a></div>
	</section>
	<section class="realm">
		<div class="heading midgard">Midgard</div>
		<div class="base">Guardian</div>
		<div class="class"><a href="/berserker">Berserker</a></div>
		<div class="class"><a href="/warrior">Warrior</a></div>
		<div class="class"><a href="/skald">Skald</a></div>
		<div class="class"><a href="/thane">Thane</a></div>
		<div class="class"><a href="/savage">Savage</a></div>
		<div class="base">Seer</div>
		<div class="class"><a href="/healer">Healer</a></div>
		<div class="class"><a href="/shaman">Shaman</a></div>
		<div class="base">Rogue</div>
		<div class="class"><a href="/hunter">Hunter</a></div>
		<div class="class"><a href="/shadowblade">Shadowblade</a></div>
		<div class="base">Mystic</div>
		<div class="class"><a href="/runemaster">Runemaster</a></div>
		<div class="class"><a href="/spiritmaster">Spiritmaster</a></div>
		<div class="class"><a href="/bonedancer">Bonedancer</a></div>
	</section>
</main>

<style>
	main {
		display: flex;
		justify-content: center;
		padding-bottom: 100px;
	}

	section.realm {
		width: 300px;
	}

	.heading {
		display: flex;
		justify-content: center;
		align-items: center;
		margin-top: 10px;
		font-weight: bold;
		font-size: 20px;
	}

	.heading.albion {
		color: var(--red);
	}

	.heading.hibernia {
		color: var(--green);
	}

	.heading.midgard {
		color: var(--blue);
	}

	.base {
		margin-top: 10px;
		margin-bottom: 10px;
		text-transform: capitalize;
	}

	.class {
		color: var(--yellow);
		text-align: center;
		text-transform: capitalize;
	}

	.class:hover {
		color: white;
		background-color: var(--gray-dark);
	}

	.class a {
		display: block;
		width: 100%;
	}
</style>
