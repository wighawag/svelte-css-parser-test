<script>
	let name = 'world';
</script>

<button class="button ~positive !normal">Hello {name}!</button>

<style>
	:root {
    --color-transparent: transparent;
    --color-neutral: #718096;
    --color-neutral-light: #e2e8f0;
    --color-neutral-low-title: #1a202c;
    --color-neutral-low-content: #4a5568;
    --color-neutral-low-fill: transparent;
    --color-neutral-low-background: #fff;
    --color-neutral-low-muted: #4a5568;
    --color-neutral-normal-content: #2d3748;
    --color-neutral-normal-fill: #edf2f7;
    --color-neutral-normal-background: #f7fafc;
    --color-neutral-normal-muted: #4a5568;
    --color-neutral-high-content: #fff;
    --color-neutral-high-fill: #4a5568;
    --color-neutral-high-muted: #e2e8f0;
    --color-positive: #48bb78;
    --color-positive-low-title: #2f855a;
    --color-positive-low-content: #38a169;
    --color-positive-low-fill: transparent;
    --color-positive-low-background: #fff;
    --color-positive-low-muted: #48bb78;
    --color-positive-normal-content: #276749;
    --color-positive-normal-fill: #c6f6d5;
    --color-positive-normal-background: #f0fff4;
    --color-positive-normal-muted: #38a169;
    --color-positive-high-content: #fff;
    --color-positive-high-fill: var(--color-positive);
    --color-positive-high-muted: #f0fff4;
    --color-warning: #ecc94b;
    --color-warning-low-title: #975a16;
    --color-warning-low-content: #b7791f;
    --color-warning-low-fill: transparent;
    --color-warning-low-background: #fff;
    --color-warning-low-muted: #d69e2e;
    --color-warning-normal-content: #975a16;
    --color-warning-normal-fill: #fefcbf;
    --color-warning-normal-background: ivory;
    --color-warning-normal-muted: #d69e2e;
    --color-warning-high-content: #744210;
    --color-warning-high-fill: #f6e05e;
    --color-warning-high-muted: #975a16;
    --color-critical: #f56565;
    --color-critical-low-title: #c53030;
    --color-critical-low-content: #e53e3e;
    --color-critical-low-fill: transparent;
    --color-critical-low-background: #fff;
    --color-critical-low-muted: #f56565;
    --color-critical-normal-content: #9b2c2c;
    --color-critical-normal-fill: #fed7d7;
    --color-critical-normal-background: #fff5f5;
    --color-critical-normal-muted: #e53e3e;
    --color-critical-high-content: #fff;
    --color-critical-high-fill: var(--color-critical);
    --color-critical-high-muted: #fff5f5;
    --color-info: #4299e1;
    --color-info-low-title: #2b6cb0;
    --color-info-low-content: #3182ce;
    --color-info-low-fill: transparent;
    --color-info-low-background: #fff;
    --color-info-low-muted: #4299e1;
    --color-info-normal-content: #2c5282;
    --color-info-normal-fill: #bee3f8;
    --color-info-normal-background: #ebf8ff;
    --color-info-normal-muted: #3182ce;
    --color-info-high-content: #fff;
    --color-info-high-fill: var(--color-info);
    --color-info-high-muted: #ebf8ff;
    --color-urge: #805ad5;
    --color-urge-low-title: #6b46c1;
    --color-urge-low-content: #805ad5;
    --color-urge-low-fill: transparent;
    --color-urge-low-background: #fff;
    --color-urge-low-muted: #9f7aea;
    --color-urge-normal-content: #553c9a;
    --color-urge-normal-fill: #e9d8fd;
    --color-urge-normal-background: #faf5ff;
    --color-urge-normal-muted: #805ad5;
    --color-urge-high-content: #fff;
    --color-urge-high-fill: var(--color-urge);
    --color-urge-high-muted: #faf5ff;
    --color-content: var(--color-neutral-low-content);
    --color-fill: var(--color-transparent);
    --color-background: var(--color-transparent);
    --color-muted: var(--color-neutral-low-muted);
    --color-core: var(--color-neutral);
    --color-light: var(--color-neutral-light);
    --color-title: var(--color-neutral-low-title);
    --color-icon: var(--color-content);
    --fallback-box-shadow-low: 0 0 0 0 transparent;
    --fallback-box-shadow-normal: 0 1px 3px 0 rgba(0, 0, 0, 0.1),
      0 1px 2px 0 rgba(0, 0, 0, 0.06);
    --fallback-box-shadow-high: 0 4px 6px -1px rgba(0, 0, 0, 0.1),
      0 2px 4px -1px rgba(0, 0, 0, 0.06);
    --fallback-box-shadow: var(--fallback-box-shadow-normal);
    --family-primary: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
      Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif,
      "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol",
      "Noto Color Emoji";
    --family-secondary: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
      Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif,
      "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol",
      "Noto Color Emoji";
    --text-rendering-mode: optimizeLegibility;
    --body-line-height: 1.5;
  }
 .button {
    background-color: transparent;
    background-color: var(--color-fill);
    color: #4a5568;
    color: var(--color-content);
    display: inline-flex;
    flex-direction: row;
    flex-wrap: nowrap;
    align-items: center;
    align-content: center;
    justify-content: space-between;
    cursor: pointer;
    position: relative;
    line-height: 1.5;
    line-height: var(--button-line-height, 1.5);
    white-space: nowrap;
    transition: -webkit-filter 75ms linear;
    transition: -webkit-filter var(--button-transition-speed, 75ms) linear;
    transition: filter 75ms linear;
    transition: filter var(--button-transition-speed, 75ms) linear;
    transition: filter 75ms linear, -webkit-filter 75ms linear;
    transition: filter var(--button-transition-speed, 75ms) linear,
      -webkit-filter var(--button-transition-speed, 75ms) linear;
    transform-origin: center;
    text-decoration: none;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    border-radius: 0.25rem;
    padding: 0.25rem 0.5rem;
    outline: 0;
  }
  .button:focus:not([disabled]):not(.field),
  .button:hover:not([disabled]):not(.field) {
    -webkit-filter: brightness(95%);
    -webkit-filter: brightness(var(--button-filter-brightness, 95%));
    filter: brightness(95%);
    filter: brightness(var(--button-filter-brightness, 95%));
  }
  .\~positive {
    --color-content: var(--color-positive-normal-content);
    --color-fill: var(--color-positive-normal-fill);
    --color-background: var(
      --color-positive-normal-background,
      var(--color-fill)
    );
    --color-muted: var(--color-positive-normal-muted);
    --color-title: var(
      --color-positive-normal-title,
      var(--color-positive-normal-content)
    );
    --color-core: var(--color-positive);
    --color-light: var(--color-positive-light, var(--color-core));
    --color-icon: var(--color-positive-normal-muted);
  }
  .\~positive.\!normal {
    --color-content: var(--color-positive-normal-content);
    --color-fill: var(--color-positive-normal-fill);
    --color-background: var(
      --color-positive-normal-background,
      var(--color-fill)
    );
    --color-muted: var(--color-positive-normal-muted);
    --color-title: var(
      --color-positive-normal-title,
      var(--color-positive-normal-content)
    );
    --color-icon: var(--color-positive-normal-muted);
  }
</style>