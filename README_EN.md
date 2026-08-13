# Budget Inception Poster

[中文](README.md) · [English](README_EN.md)

Turn an ordinary photo into a tourist check-in from a place that does not exist. The person and the physical ground remain real; a monumental upside-down world hangs above them.

> Sit at the edge of reality. Check in to a world that never existed.

<p align="center">
  <img src="examples/whale.webp" width="31%" alt="Inverted whale ocean">
  <img src="examples/space-station.webp" width="31%" alt="Inverted orbital station">
  <img src="examples/data-center.webp" width="31%" alt="Inverted cloud data center">
</p>

## Origin

The idea began during my daily commute past Guomao in Beijing, where I kept seeing people line up for the same popular photo spot. That made me wonder: what if taking the picture required no queue—and the scenery did not have to stay the same? An ordinary person could remain seated at the edge of reality while any monumental world hung upside down above them. That question became this project.

## Core Structure

- **Keep reality fixed below:** preserve the person, pose, clothes, platform, diagonal edge, camera angle, and shadow.
- **Change the dream above:** generate an inverted whale ocean, orbital station, pyramid complex, Louvre courtyard, data center, or another monumental world.
- **Preserve the void:** leave a large quiet field between mundane reality and fabricated spectacle.
- **Avoid graphic decoration:** the irony comes from the contrast itself, not from typography or poster effects.

## Two Modes

### Specified Dream

Upload a photo and name the world you want overhead:

```text
Use @budget-inception-poster and place a monumental upside-down
orbital station above the person.
```

### Random Dream

Upload a photo without naming a theme:

```text
Use @budget-inception-poster. Random dream.
```

The skill chooses a high-contrast subject from geometric landmarks, technological structures, natural giants, cultural spaces, and urban worlds.

## More Experiments

<p align="center">
  <img src="examples/pyramids.webp" width="31%" alt="Inverted Giza pyramids">
  <img src="examples/louvre.webp" width="31%" alt="Inverted Louvre">
  <img src="examples/imperial-palace.webp" width="31%" alt="Inverted Chinese imperial palace">
</p>

## Best Source Photos

- Vertical composition
- A person sitting on a platform, rooftop, stair, or another hard edge
- The person placed near the bottom
- A large clean sky or blank region above
- Ordinary clothes and an unremarkable pose—the more mundane, the stronger the contrast

## Visual Formula

```text
ordinary person + real platform + large empty field
+ monumental upside-down world
= a deliberately fabricated tourist check-in
```

## Installation

Install `SKILL.md` together with the `references/` directory as one skill folder. Trigger it with:

```text
@budget-inception-poster
```

## License

MIT
