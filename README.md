# necromancer
(Re)animating a Walmart skeleton with Raspberry Pi and computer vision.

## Feature List
- [ ] Can see with a camera
- [ ] Can hear with a microphone
- [ ] Can hear with a microphone array
- [ ] Can speak via a speaker
- [ ] Can rotate head
- [ ] Can rotate left arm
- [ ] Can rotate right arm
- [ ] Can identify presence and location of faces
- [ ] Can recognize faces from trained images
- [ ] Can follow faces with head rotation
- [ ] Can open/close mouth
- [ ] Can transcribe heard speech to text
- [ ] Can use speech to text
- [ ] Can interact with LLMs

## Imagined API Example

```
ryan = Skeleton()

target = ryan.find_face()

if target is not None:
  ryan.look_at(target)

ryan.say("Hello!")
prompt = ryan.listen()
response = ryan.process(prompt)
ryan.say(response)
```
