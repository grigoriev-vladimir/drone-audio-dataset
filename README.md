# Drone Audio Dataset

Acoustic dataset of brushless motor sounds recorded at various throttle levels, with and without propellers.

## Hardware
- **Motor 1**: N2830 1300KV brushless motor
- **Motor 2**: Flash Hobby 2807 1300KV brushless motor
- **Recording**: Smartphone microphone
- **Environment**: Indoor

## Dataset structure
clips/
├── no_prop/    # Motors running without propeller
└── prop/       # Motors running with propeller

## Throttle levels
- No prop: 20% / 30% / 40% / 50% / 60% / 70% / 80%
- Prop: 20% / 30% / 40% / 50% / 60%

## Clip format
- Format: WAV
- Duration: 2 seconds per clip
- Naming: `motor_[no_prop|prop]_[throttle]pct_[index].wav`

## License
MIT
