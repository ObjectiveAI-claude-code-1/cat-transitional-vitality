# cat-transitional-vitality

Ranks cat photographs by **transitional vitality** — the degree to which each image captures a cat in the act of becoming rather than settled in a stable state of being. The function asks a deceptively simple question of each image: *is this cat between things?*

## Input

An array of **2 or more cat images**. Each element is a photograph of a cat to be evaluated and ranked against the others.

```
[image_1, image_2, image_3, ...]
```

## Output

A vector of scores, one per input image, representing relative transitional vitality. Higher scores indicate images where the cat is more vividly caught between states. The scores form a probability distribution that can be used to rank, sort, or filter the input images.

## What It Evaluates

The function evaluates three distinct qualities of transitional vitality. Each addresses a different dimension of what it means for a cat to be captured between states, and together they form a complete picture.

### 1. Kinetic Imprint

The degree to which the cat's physical body bears visible evidence of motion in progress. This is the most concrete quality — it lives in the architecture of the body itself.

**Scores high:**
- A cat mid-stretch, spine arched beyond resting curvature, paws extended to full reach
- A cat shifting from sitting to standing with weight distributed unevenly
- A head in the act of turning, visible in asymmetric features or slight blur
- A cat mid-leap, unsupported by any surface, gravity a visible participant
- Postural asymmetry, uneven shoulder blades, a tail mid-swing

**Scores low:**
- A cat sitting symmetrically with paws tucked and tail wrapped
- A cat in steady, uniform sprint with no visible state change
- Any posture that communicates permanence — a shape the cat could hold indefinitely

### 2. Emotional Flux

The degree to which the cat's internal state appears to be shifting visibly across its face, eyes, ears, and overall bearing. Where kinetic imprint reads the body, emotional flux reads the mind.

**Scores high:**
- A sleeping cat's eyes opening, awareness flooding back into the face
- A playful cat freezing into sudden uncertainty — two states competing simultaneously
- An aloof cat softening into affection as it begins to lean toward a hand
- The instant curiosity ignites: pupils dilating, head tilting, attention snapping toward a stimulus
- Any expression that is legibly between two emotional states

**Scores low:**
- A single stable expression: purely calm, purely alert, purely annoyed, purely content
- A face that reads as a fixed portrait with no sense of shift
- Settled, resolved emotional postures with no competing states

### 3. Narrative Tension

The degree to which the image as a whole implies a before and an after, creating the sensation that this frame has been pulled from a continuous, unfolding sequence of living experience.

**Scores high:**
- A cat on the edge of a countertop, paw extended into open air, about to leap
- A cat in a doorway between rooms, implying passage between spaces
- A cat whose gaze is fixed on something beyond the frame, implying an impending response
- Any composition where you can sense what the cat was just doing and what it is about to do

**Scores low:**
- A cat centered in a space with no implied trajectory
- Temporally flat images — the cat could have been in this position for seconds or hours
- Compositions with no environmental cues suggesting transition or passage

## Use Cases

- **Content curation**: Surface the most alive and arresting cat images for social media feeds, editorial selection, or recommendation systems
- **Photography workflows**: Help photographers review large sets of frames from a shoot and surface the most dynamic, emotionally resonant captures
- **Reference material**: Find images that convey movement, tension, and the texture of lived experience for artists, designers, or researchers
- **Quality filtering**: Separate images that pulse with the energy of a moment in progress from images that merely document a moment already resolved

## Key Distinctions

This function does **not** simply detect motion versus stillness. A sleeping cat scores low, but so can a cat in full sprint if the sprint appears steady and uniform. What matters is the visible evidence that the cat is *passing through* — that the image has captured a threshold rather than a destination. The highest-scoring images are those where body, emotion, and composition all converge to refuse to let time stand still.