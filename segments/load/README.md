# Load

## Installation

To use this segment, you need to activate it by adding it to your
`P9K_LEFT_PROMPT_ELEMENTS` or `P9K_RIGHT_PROMPT_ELEMENTS` array, depending
where you want to show this segment.

## Configuration

Displays one of your load averages with appropriate state coloring. The thresholds are:
- `0.7 * NUM_CORES <`: critical
- `0.5 * NUM_CORES <`: warning
- `less`: normal

| Variable | Default Value | Description |
|----------|---------------|-------------|
|`P9K_LOAD_WHICH`|5|Which average to show. Possible values: 1, 5 or 15|