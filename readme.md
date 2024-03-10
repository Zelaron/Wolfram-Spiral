![Wolfram spirals](https://github.com/Ionosi/assets/blob/main/examples.jpg?raw=true)

# Wolfram-Spiral

This project features a web-based tool for generating and visualizing an analogue of Wolfram's cellular automaton in a unique spiral pattern. It offers user customization to create diverse visual patterns.

## Features

- **Dynamic Generation**: Creates a spiral pattern based on cellular automaton rules, where the coloring of the current cell is determined by the colors of the neighboring eight cells.
- **Customization**: Customize canvas size, color count, and automaton rules through URL parameters.
- **Regeneration Option**: Easily regenerate the pattern with new or specified configurations.

## How to Use

1. **Open in Browser**: Launch `wolfram-spiral.html` in any modern web browser to view a randomized pattern.
2. **Customization (Optional)**: Use URL parameters for customization:
   - `sidelength`: Sets the sidelength of the square canvas (default 700).
   - `colors`: Number of colors (default 3).
   - `rule`: Specifies a particular rule for pattern generation (random by default).
   - `verbose`: Set to `true` to display the rule on the page.

   Example URL: `file:///path/to/wolfram-spiral.html?sidelength=800&colors=5&verbose=true`

3. **Regenerate Pattern**: Click "Regenerate pixels" for a new random pattern.

## Generating a Specific Pattern

To regenerate a specific pattern:
1. Open the pattern with the `verbose` parameter set to `true`.
2. Note the 'Rule' displayed on the page.
3. To recreate this pattern later, append `?rule=YourRuleHere` to the URL, replacing `YourRuleHere` with the noted rule.

   Example: `file:///path/to/wolfram-spiral.html?rule=2c001111011001...`

## How it Works

The script generates a canvas-based pattern using cellular automaton rules. Unlike traditional top-to-bottom generation of Wolfram's elementary cellular automaton, this script renders in a spiral pattern from the canvas center.

## Contributing

Contributions are welcome! Feel free to fork, modify, and submit pull requests to enhance functionality or visual design.
