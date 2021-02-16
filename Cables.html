<template>
	<main class="container">
		<div class="input-wrap">
			<svg 
				class="cloudy"
				viewBox="0 0 277 145"
			>
				<path 
					class="cloudy-poofs"
					d="M218,20c-0.74,0-1.47,0.03-2.2,0.06C204.99,7.77,189.16,0,171.5,0c-12.22,0-23.58,3.72-33,10.09 C129.08,3.72,117.72,0,105.5,0C87.84,0,72.01,7.77,61.2,20.06C60.47,20.03,59.74,20,59,20C26.42,20,0,46.42,0,79 c0,32.58,26.42,59,59,59c5.26,0,10.36-0.7,15.21-1.99C83.28,141.7,94,145,105.5,145c12.22,0,23.58-3.72,33-10.09 c9.42,6.37,20.78,10.09,33,10.09c11.5,0,22.22-3.3,31.29-8.99c4.85,1.29,9.95,1.99,15.21,1.99c32.58,0,59-26.42,59-59 C277,46.42,250.58,20,218,20z"
				/>
			</svg>
			<div 
				v-if="emailText"
				class="input-text"
			>
				<span 
					v-for="(letter, index) in emailText" 
					:key="index"
					class="input-text-letter"
				>{{ letter }}</span>
			</div>
			<!-- <dreamy-input 
				v-model="emailValue" 
				:disabled="emailIsDisabled"
				:has-error="isNotValid"
				@click="submitMail"
				@keydown.enter="submitMail"
			/> -->
			<div 
				:class="{ disabled: emailIsDisabled }"
				class="dreamy-input"
			>
				<label 
					class="dreamy-input-label"
					for="dreamyInput"
				>Email</label>
				<input 
					id="dreamyInput"
					v-model="emailValue"
					:aria-describedby="isNotValid ? 'dreamyInputErr' : null"
					:disabled="emailIsDisabled"
					autocomplete="off"
					class="dreamy-input-control"
					type="email"
					@keydown.enter="submitMail"
				>
				<transition name="fade">
					<span 
						v-if="isNotValid"
						id="dreamyInputErr"
						class="dreamy-input-error"
					>
						Please enter a valid email.
					</span>
				</transition>
				<button
					aria-label="Subscribe"
					class="dreamy-input-button"
					@click="submitMail"
				>
					<svg 
						class="dreamy-input-button-svg"
						viewBox="0 0 35 35"
					>
						<path 
							class="dreamy-input-button-star" 
							d="M29.36,23.14l4.63-5.32c2.08-2.39,0.77-6.08-2.39-6.7l-5.23-1.02c-0.23-0.05-0.44-0.19-0.56-0.39l-4.67-7.7 c-1.64-2.69-5.64-2.69-7.27,0l-4.67,7.7c-0.12,0.2-0.33,0.34-0.56,0.39L3.4,11.13c-3.16,0.62-4.47,4.31-2.39,6.7l4.63,5.32 c0.17,0.2,0.24,0.47,0.18,0.73L4.31,29.9c-0.83,3.32,2.61,6.12,5.82,4.74l7.03-3.03c0.22-0.09,0.47-0.09,0.68,0l7.03,3.03 c3.21,1.38,6.65-1.42,5.82-4.74l-1.51-6.04C29.12,23.61,29.18,23.34,29.36,23.14z"
						/>
					</svg>
				</button>
			</div>
		</div>
		<kirby 
			:swallow="isValid"
			:spit="isNotValid"
			@animationdone="reset"
		/>
	</main>
</template>

<script>
// import DreamyInput from './components/DreamyInput.vue'
import Kirby from 'https://codepen.io/tiffachoo/pen/fffe3dbfb989c5a7b57e69674f0e0184.js';


export default {
	name: 'aCoolAppByTiffachoo',
	components: {
		Kirby
		// DreamyInput
	},
	data() {
		return {
			emailValue: '',
			emailIsDisabled: false,
			emailText: '',
			isValid: false,
			isNotValid: false
		}
	},
	methods: {
		submitMail() {
			if (this.emailValue) {
				const emailRegex = /^(([^<>()[\]\\.,;:\s@"]+(\.[^<>()[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;
				this.isValid = emailRegex.test(this.emailValue);
				this.isNotValid = !this.isValid;

				this.emailText = this.emailValue.length > 15 ?
					this.emailValue.slice(0, 15) + '...' :
					this.emailValue;
				this.emailValue = '';
				this.emailIsDisabled = true;
	
				this.$nextTick(this.animateText);
			}
		},
		animateText() {
			const tlJiggle = gsap.timeline({ 
				delay: 1, 
				defaults: {
					duration: 0.1
				}
			});
			
			tlJiggle
				.to('.input-text-letter', {
					y: 'random(-6, 4)'
				})
				.to('.input-text-letter', {
					y: 'random(-6, 4)'
				})
				.to('.input-text-letter', {
					y: 'random(-6, 4)'
				})
				.to('.input-text-letter', {
					y: 'random(-6, 4)'
				})
				.to('.input-text-letter', {
					y: 0,
					duration: 0.1
				})
				.to('.input-text-letter', {
					delay: 0,
					duration: 0.5,
					ease: 'expo.in',
					x: 300,
					stagger: {
						amount: 0.3,
						from: 'end'
					}
				});
		},
		reset() {
			this.emailIsDisabled = false;
			this.isValid = false;
			this.isNotValid = false;
			this.emailText = '';
		}
	}
}
</script>

<style lang="scss">
$black: #87213c;
$white: #fff;

$primary-color: #f9dde3;
$primary-color-tint: #fcf2f5;
$secondary-color: #ff2961;
$accent-color: #fae798;

$mail-color: #326dcc;
$star-sparkly-color: #b8d7ff;

$primary-font: 'Fredoka One', sans-serif;

:root {
	--black: #{$black};
	--white: #{$white};
	--primary-color: #{$primary-color};
	--primary-color-tint: #{$primary-color-tint};
	--secondary-color: #{$secondary-color};
	--accent-color: #{$accent-color};
	--mail-color: #{$mail-color};
	--star-color: #{$accent-color};
	--star-sparkly-color: #{$star-sparkly-color};
}
	
@import url('https://fonts.googleapis.com/css2?family=Fredoka+One&display=swap');
	
* { box-sizing: border-box; }

body {
	display: grid;
	place-items: center;
	min-height: 100vh;
	background-color: var(--primary-color-tint);
	font-size: 16px;
	line-height: 1;
	font-family: $primary-font;
}

.container {
	display: grid;
	grid-template-columns: 2fr 1fr;
	align-items: center;
	width: 100%;
	max-width: 400px;
}

.input-text {
	position: absolute;
	z-index: 5;
	width: 17rem;
	font-size: 1.25rem;
	line-height: 1.5;
	color: var(--black);
	transform: translate(1rem, 0.625rem);
	overflow: hidden;

	&-letter {
		display: inline-block;
		transform-origin: center bottom;
	}
}

.input-wrap {
	position: relative;
}

.cloudy {
	position: absolute;
	top: 50%;
	left: 50%;
	width: 150%;
	transform: translate(-50%, -50%);

	&-poofs {
		fill: var(--white);
	}
}

.fade {
	&-enter-active,
	&-leave-active {
		transition: 0.3s;
	}

	&-enter-from,
	&-leave-to {
		opacity: 0;
	}
}
	
.dreamy-input {
	--offset-top: 0.1875rem;
	--offset-left: -0.125rem;
	--control-height: 3.125rem;

	position: relative;

	&::after {
		content: '';
		position: absolute;
		top: var(--offset-top);
		left: var(--offset-left);
		height: 100%;
		width: 100%;
		border: 3px solid var(--black);
		pointer-events: none;
		transition: border 0.5s ease-in-out;
	}

	&::after,
	&-control {
		border-radius: var(--control-height);
	}

	&-control {
		width: 15.625rem;
		height: var(--control-height);
		padding: 0 calc(1rem + var(--control-height)) 0 1rem;
		border: 0;
		background-color: var(--primary-color);
		font-family: $primary-font;
		font-size: 1.25rem;
		color: var(--black);
		caret-color: var(--secondary-color);
		transition: background-color 0.5s ease-in-out;

		&:focus {
			outline: none;
		}

		&:disabled {
			background-color: var(--primary-color-tint);
		}
	}

	&:focus-within {
		&::after {
			border-color: var(--secondary-color);
		}
	}

	&-label,
	&-error {
		position: absolute;
		left: 1rem;
		font-size: 0.75rem;
		letter-spacing: 0.05em;
	}

	&-label {
		top: -0.75rem;
		color: var(--black);
	}

	&-error {
		bottom: -1.5rem;
		color: var(--secondary-color);
	}

	&-button {
		display: grid;
		place-items: center;
		position: absolute;
		top: calc(var(--offset-top) + 3px);
		right: 0;
		height: var(--control-height);
		width: var(--control-height);
		padding: 0;
		border: 0;
		background-color: transparent;
		color: var(--white);
		cursor: pointer;
		transition: 0.4s ease-in-out;

		&-star {
			fill: currentColor;
			stroke: var(--star-stroke, transparent);
			stroke-width: 3px;
		}

		&-svg {
			width: 40%;
			overflow: visible;
		}

		&:focus {
			outline: none;
			color: var(--secondary-color);
		}

		&:hover {
			--star-stroke: var(--black);
			transform: scale(1.2);
			color: var(--accent-color);
		}
	}

	&.disabled {
		&::after {
			border-color: var(--primary-color);
		}

		.dreamy-input-button {
			color: var(--primary-color);
		}
	}
}
</style>
