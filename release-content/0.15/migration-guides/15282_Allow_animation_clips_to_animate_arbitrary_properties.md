- Animation keyframes are now an extensible trait, not an enum. Replace `Keyframes::Translation(...)`, `Keyframes::Scale(...)`, `Keyframes::Rotation(...)`, and `Keyframes::Weights(...)` with `Box::new(TranslationKeyframes(...))`, `Box::new(ScaleKeyframes(...))`, `Box::new(RotationKeyframes(...))`, and `Box::new(MorphWeightsKeyframes(...))` respectively.