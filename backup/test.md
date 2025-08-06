<div class="gravatar-hovercard"><style></style>
			<div class="gravatar-hovercard__inner">
				
				<div class="gravatar-hovercard__header">
					<a class="gravatar-hovercard__avatar-link" href="https://gravatar.com/altracem?utm_source=hovercard" target="_blank">
						<img class="gravatar-hovercard__avatar" src="https://1.gravatar.com/avatar/22c4bf106ce79ff964352615b4c9b392bcad31c028beb12a3dd062a47a6f5be5?s=256" width="104" height="104" alt="Altrace">
					</a>
					<a class="gravatar-hovercard__personal-info-link" href="https://gravatar.com/altracem?utm_source=hovercard" target="_blank">
						<h4 class="gravatar-hovercard__name">Altrace</h4>
						
						<p class="gravatar-hovercard__location">Xi'an</p>
					</a>
				</div>
				<div class="gravatar-hovercard__body">
								<p class="gravatar-hovercard__description">喵喵~</p>
							</div>
				<div class="gravatar-hovercard__social-links">
					<a class="gravatar-hovercard__social-link" href="https://gravatar.com/altracem?utm_source=hovercard" target="_blank" data-service-name="gravatar">
						<img class="gravatar-hovercard__social-icon" src="https://s.gravatar.com/icons/gravatar.svg" width="32" height="32" alt="Gravatar">
					</a>
					
					<a class="gravatar-hovercard__social-link" href="https://x.com/altracem" target="_blank" data-service-name="twitter">
						<img class="gravatar-hovercard__social-icon" src="https://s.gravatar.com/icons/x.svg" width="32" height="32" alt="X">
					</a>
				
				</div>
				
				<div class="gravatar-hovercard__footer">
					<a class="gravatar-hovercard__profile-url" title="https://gravatar.com/altracem" href="https://gravatar.com/altracem?utm_source=profile-card" target="_blank">
						gravatar.com/altracem
					</a>
					<a class="gravatar-hovercard__profile-link" href="https://gravatar.com/altracem?utm_source=profile-card" target="_blank">
						View profile →
					</a>
				</div>
				
				
				<div class="gravatar-hovercard__profile-color" style="background: rgb(227, 234, 252);"></div>
			</div>
		<script>
		const hovercardInner = document.querySelector('.gravatar-hovercard__inner');

		function openDrawer( target, container ) {
			const selector = '.gravatar-hovercard__drawer[data-drawer-name="' + target.dataset.targetDrawer + '"]';
			const drawer = container.querySelector( selector );
			drawer?.classList.add( 'gravatar-hovercard__drawer--open' );
		}

		function closeDrawer( target, container ) {
			const selector = '.gravatar-hovercard__drawer[data-drawer-name="' + target.dataset.targetDrawer + '"]';
			const drawer = container.querySelector( selector );
			drawer?.classList.add( 'gravatar-hovercard__drawer--closing' );
			drawer?.classList.remove( 'gravatar-hovercard__drawer--open' );

			setTimeout( () => {
				drawer?.classList.remove( 'gravatar-hovercard__drawer--closing' );
			}, 300 );
		}

		hovercardInner.querySelectorAll( '.gravatar-hovercard__button' ).forEach( ( el ) => {
			el.addEventListener( 'click', () => openDrawer( el, hovercardInner ) );
		} );
		hovercardInner.querySelectorAll( '.gravatar-hovercard__drawer-close' ).forEach( ( el ) => {
			el.addEventListener( 'click', () => closeDrawer( el, hovercardInner ) );
		} );
		hovercardInner.querySelectorAll( '.gravatar-hovercard__drawer-backdrop' ).forEach( ( el ) => {
			el.addEventListener( 'click', () => closeDrawer( el, hovercardInner ) );
		} );
	</script></div>