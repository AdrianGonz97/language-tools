{#snippet foo(x)}
	<div>asd{x}</div>
{/snippet}

{@render foo(1)}
{@render foo()}

<Component>
	<div>{asd}</div>
	{#snippet bar(x)}
		<div>asd{x}</div>
	{/snippet}
</Component>