# Results, generated from the scorecards

## Checkpoints, in-distribution (the desk layout the training data used)

| Run | Placed (95% CI) | Fell | Failure types |
|---|---|---|---|
| checkpoint-2500 | 36/50 (72%, 58–83%) | 0 | – |
| checkpoint-5000 | 24/50 (48%, 35–61%) | 0 | – |
| checkpoint-10000 | 49/50 (98%, 90–100%) | 0 | – |
| checkpoint-15000 | 49/50 (98%, 90–100%) | 0 | – |
| checkpoint-20000 | 190/200 (95%, 91–97%) | 0 | – |

## Held-out: objects 12 cm outside the training range, seeds from 100000

| Run | Placed (95% CI) | Fell | Failure types |
|---|---|---|---|
| checkpoint-20000 | 69/100 (69%, 59–77%) | 0 | no grip 2, knocked away 23, held at end 1, missed plate 2, dropped in transit 1, placed not held 2 |

## Old default contacts against grasping contacts, the same 100 seeds

| Run | Placed (95% CI) | Fell | Failure types |
|---|---|---|---|
| default_contacts | 96/100 (96%, 90–98%) | 0 | knocked away 2, missed plate 1, dropped in transit 1 |
| grasping_contacts | 99/100 (99%, 95–100%) | 0 | knocked away 1 |

## Vision conditions (old contacts), 100 episodes each, paired with the baseline

| Run | Placed (95% CI) | Fell | Failure types |
|---|---|---|---|
| baseline | 98/100 (98%, 93–99%) | 0 | – |
| camera_turn | 93/100 (93%, 86–97%) | 0 | – |
| clutter | 92/100 (92%, 85–96%) | 0 | – |
| low_light | 94/100 (94%, 88–97%) | 0 | – |
| reworded | 96/100 (96%, 90–98%) | 0 | – |
| side_light | 94/100 (94%, 88–97%) | 0 | – |
| state_noise | 96/100 (96%, 90–98%) | 0 | – |

## Dynamics conditions (grasping contacts), 100 episodes each, paired with the baseline

| Run | Placed (95% CI) | Fell | Failure types |
|---|---|---|---|
| baseline | 99/100 (99%, 95–100%) | 0 | knocked away 1 |
| heavy_apple | 100/100 (100%, 96–100%) | 0 | none |
| light_apple | 99/100 (99%, 95–100%) | 0 | missed plate 1 |
| slippery_surfaces | 99/100 (99%, 95–100%) | 0 | missed plate 1 |
| waxy_apple | 99/100 (99%, 95–100%) | 0 | missed plate 1 |
