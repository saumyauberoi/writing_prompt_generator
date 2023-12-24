import random
def generate_prompt():
    genre=["science fiction","historical fiction","contemporary","thriller","adventure","fantasy"]
    theme=["identity","artificial intelligence and ethics","cannibalism as a symbol of desire","parallel universes","forgiveness and redemption","survival in the wilderness","the power of dreams","eternal youth and immortality","unlikely friendships","mind control and manipulation","environmental apocalypse","political intrigue","lost civilisation","time travel paradoxes"]
    setting=["a magical library","an underwater research facility","a subterranean city","a lost space colony","a deserted amusement park","a haunted Victorian mansion","an enchanted forest","a bustling metropolis","a medieval kingdom","a remote island","a futuristic city","a time-looped village","an ephemeral dream realm","an inhabited space station","post-apocalyptic megacity ruins","a mystical swamp with living trees","a celestial observatory"]
    protagonist=["an eccentric scientist","a rogue archaeologist","a time-travelling historian","a shape-shifting detective","an amnesiac adventurer","an exiled space explorer","a cursed heir","a teleporting wanderer","a dream-weaving artist","a cursed puppeteer","a struggling musician","a single parent entrepreneur","a small-town detective","an aspiring chef","a rural school teacher","a freelance photographer","a commuter cyclist","a high school counsellor","an ambitious journalist","a misunderstood artificial intelligence"]
    conflict=["avenging a loved one's murder","revealing a family curse","cracking a cybersecurity conspiracy","surviving a kidnapping or hostage situation","rekindling a past romance","escaping a supernatural phenomenon","uncovering family betrayal","preventing a biological pandemic","discovering a hidden secret","uncovering a government conspiracy","solving a series of mysterious events","finding true love against all odds","surviving in a post-apocalyptic world","revealing a cult's darkest secrets","challenging a corrupt education system","navigating a small-town scandal"]
    obstacle=["a lethal bioweapon threat","disastrous climate change effects","a cyberspace hacker threat","a cursed artifact's influence","genetic modification gone awry","sudden dimensional rifts","memory-altering technology","an invasive alien species","a time-loop paradox","memory-wiping epidemic","interplanetary resource war","a forbidden love affair","a plague of dream invaders","a cryptic prophecy's unfolding","a custody battle over children"]
    prompt=f"{random.choice(genre)} write-up set in {random.choice(setting)} with {random.choice(protagonist)} {random.choice(conflict)}, facing {random.choice(obstacle)}, and exploring the theme of {random.choice(theme)}."
    return prompt
if __name__=="__main__":
    writing_prompt=generate_prompt()
    print(writing_prompt)
