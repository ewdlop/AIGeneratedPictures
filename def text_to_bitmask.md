# def text_to_bitmask

``` 
def text_to_bitmask(text):
    """Convert text into a bitmask representation."""
    bitmask = ''.join(format(ord(char), '08b') for char in text)
    return bitmask

text = """Imagine a dimly lit police station where a narcissistic policeman sits behind a cluttered desk. His piercing eyes scan a room full of civilians. His uniform is pristine, but his demeanor is cold and calculating. He leans back in his chair, arms crossed, exuding an air of authority that demands silent compliance. In his mind, beyond a shadow of a doubt, everyone in front of him is lying.

The room is tense; innocent people sit before him, shifting uncomfortably under his gaze. Some have been accused of minor infractions, others are simply witnesses, yet to him, all are guilty of deception. He asks pointed questions, not in search of truth, but to trap them in contradictions, to confirm the suspicions he already holds.

Meanwhile, in his own mind, he is above reproach. Any error or misjudgment on his part is excused by his belief in his righteousness. He is not doing anything wrong; he is merely upholding justice as he sees it. The thought that he could be mistaken, that he might be unfairly persecuting the innocent, never crosses his mind.

His badge is both shield and sword, a tool that validates his superiority. When challenged, he scoffs, dismissing concerns with a wave of his hand. "You think I'm wrong? You must be hiding something," he smirks. The cycle continues—suspicion breeds interrogation, interrogation breeds fear, fear is interpreted as guilt.

Justice, in his world, is not about fairness; it is about control. And as long as he is the one asking the questions, he will never be the one who is wrong."""

bitmask_result = text_to_bitmask(text)
bitmask_result[:512]  # Displaying only the first 512 bits for preview purposes
```
