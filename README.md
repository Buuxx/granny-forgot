# granny-forgot

Genre: First-person RPG, multiple endings, visual novel

Core gameplay mechanics: Point-and-click

玩家将扮演奶奶童年时期的假想朋友，重新结识年迈的奶奶，改善她的生活并帮助她完成心愿。玩家将会探索奶奶居住的小镇，尽可能的了解其他居民的生活规律/作息/爱好，通过与物品和场景互动的方式制造机遇巧合，从而间接的改变人物关系/生活状态/命运


## Gameplay

Player action (interact with objects) -> outcome (以数值衡量 Granny & NPCs change of mood, life status, schedule, relationship, etc.)

### Player actions:

- Interact with objects
    - Cannot take objects from one scene to another
    - Ways to interact
        - Put in inventory
        - Manage/use/combine items from inventory
        - Broke/repair an item
        - Hide an item
        - Use an item to trigger NPC
- Interact with the map
    - Click on and enter scenes
    - (show NPC location on map?)
- Build and manage NPC files (of their schedule/hobbies/personalities/relationships etc.)
    - How to collect info
        - Highlight keywords in text, player click on highlighted words to add info into files 
        - Click on NPC’s special behaviors (e.g. drinking coffee/crying) to add hobbies/personalities

### Game Progression:

- Tasks (e.g. helping the Granny to find a lost item)
    - triggered by interaction with objects
    - Checklist format (to keep track of game goals 
    - Core tasks + side quests 
- Completion of Tasks
    - Multiple solutions (e.g. find the original lost item vs. buy a new one)
    - Different solution leads to different outcome (that changes the status of Granny
    - Failed tasks 
- Object-NPC triggers
    - Trigger NPC to move an item from one scene to another
    - Trigger NPC to use an item
    - broke/repair/hide an item to trigger certain NPC reactions (which includes
        - change of mood
        - Reveal certain personalities/hidden secrets/etc.
        - Change of attitudes towards other NPCs
        - The use of an alternative item
- Information collections
    - Observing an event can trigger/change what the granny thinks of/is able to memorize, which can be revealed as a message above the granny showing what she’s thinking about (e.g.watching someone dancing can trigger her childhood memory. She may only remember this for a short amount of time, but it can be a chance for the player to gather more information)
- 剧情推动情节
    - 所有剧情推动情节（不受玩家控制，根据时间变化的background情节推动）都基于奶奶年迈的身体变化 - getting worse in memorizing things, fell off more often, worsen on eyesight etc…
        - 感觉从时间角度上这一点很难实现。如果奶奶身体变化基于游戏时间，而游戏时间的快慢又与玩家process这部游戏的快慢有关，development会更加不可控+降低可玩性。我们的落脚点或许应该更偏向于player对于奶奶行为的观察？（所以给玩家留更多时间去探索会更合理）
        - 或许我们可以加一些剧情，剧情推进中玩家的某些决定会让奶奶发生身体变化（记忆力变差，更容易摔倒，etc.），从而推进后续剧情去解决这些变化。奶奶身体变化是short-term的，但可能由于玩家的解决不当变成long-term
    - 玩家不能改变这些事情的发生，但是可以potentially延缓这些事情的发生
    - Potentially we could unlock a space after a specific event was triggered
        - Unlock the volcano space after the user complete the first task related to her husband
        - Enable the user to enter the volcano space, trigger the tourists to bring back some stones, or something her husband has left there

### Mood Variables: 
(some research needed for finalizing)
- Happiness
- Loneliness
- Anxiety
    - Willingness to participate in social events
- Depression
    - Willingness to help others 
- Trust
    - Willingness to trust the people around her and to accept n
- 面对自己变老/更加接近死亡 的心理状态变化

### 游戏周期&timer:
- time goes manually 
- player can decide when to move on to the next time slot after they completed all desired actions

## Set & Scene

### Player Role: 

**Imaginary friend** (intangible non-human character, can only interact with objects, cannot be seen by or communicate with Granny and NPCs )

玩家是奶奶年轻时的假想朋友。随着奶奶长大、被职业发展家庭生活琐事裹挟，这个假象朋友逐渐被奶奶忘记，只能存在于她的潜意识中。如今她老了，这个朋友从潜意识中逃出、重新活跃了起来。带着多年之前和年轻奶奶相处的记忆，这个假想朋友觉得面前这个年迈的老人很陌生--她并没有完成年少时的心愿，并不快乐，还有些健忘。于是，通过观察奶奶的生活环境生活状态心情等待，以及了解奶奶与周围邻居的关系和这些邻居的生活，玩家需要尽其所能——与物品和场景互动从而制造机遇巧合改变常态、进入奶奶的梦境——改善奶奶的生活并帮助奶奶完成心愿。但是，现在的奶奶究竟想要什么呢
- 奶奶在最开始遗忘了假想朋友
- 通过某个事件重新想起来
- 但假想朋友的存在其实反映了奶奶未能实现的价值，所以在游戏的最终，玩家需要通过帮助奶奶，让奶奶和这个假想朋友道别
- 假想朋友仍然记得奶奶年轻时的愿望，但奶奶已经不在意了
- 假想朋友想要帮助奶奶“完成心愿”，但现实早已改变，她的生活已经被现实塑造得千疮百孔，甚至当年的梦想已经无法实现。
- 但在帮助奶奶的过程中，假想朋友可能会发现：真正重要的不是完成曾经的梦想，而是帮助奶奶找到属于她现在的幸福。

### Characters:

#### Main Character
- [Granny](./characters/granny.md)

#### NPCs
- Twins
    - [twins1](./characters/twin1.md)
    - [twins2](./characters/twin2.md)
- [Delivery guy](./characters/delivery_guy.md)
- [A friend of Granny’s child](./characters/friend_of_grannys_child.md)
- [表演型人格](./characters/表演型人格.md)
- [显眼包](./characters/显眼包.md)
- [打太极老爷爷](./characters/老爷爷.md)
- [Harold](./characters/harold.md)
- [医生](./characters/doctor.md)
- [变态收藏家](./characters/变态收藏家.md)
- [内向gay guy](./characters/introvert_gay.md)
- [homeless](./characters/homeless.md)
- Patient with mental disorder

### Scenes:

#### Private spaces
- Granny house
- NPC houses

#### Public spaces
- [restaurant](./space/public_space/restaurant.md)
- [park](./space/public_space/park.md)
- [grocery store](./space/public_space/grocery_store.md)
- [hospital](./space/public_space/hospital.md)
- [post office](./space/public_space/post_office.md)
- [museum](./space/public_space/museum.md)
- Apartment entrance (can see all NPC leaving/returning home and interacting with each other
- Space behind houses (e.g. a garbage dump place behind a restaurant)

### Elements:
(more abstract ideas before they can be added into anything)
- Granny’s daughter or son sends their baby over for her to take care of
- Photo of her younger self → decrease in mood variables everytime she looks at it → can only reverse by replacing it with a new photo

### Events:

- Take an item from public spaces back to NPC’s home
    - Put the item inside NPC car when they left
        - Reaction of the NPC when noticing the item in the car (depending on personality)
            - Did not notice the item
            - Throw the item away
            - Take it home and use it themselves (“free item!?”)
        - Ways for the NPC to take the item from the car and back to home
            - Interact with the car & make warning sound → make someone in the household come down to check → trigger events listed above
            - Time/schedule matters due to different reactions triggered with different NPCs
            - Example: if the guy won’t notice the item at all, we need to wait till he’s in shower to trigger the event, so the lady would come down and bring the item up
    - Put the item inside NPC’s bag when they’re distracted

- Trigger event that cause the granny👵 and 老头👴to meet

- Trigger event that cause the granny and a 20+ 🧒 to meet (“Harold and Maude” achievement)
    - Consider - if this event is triggered, we are going with the ending where the granny 找到自我, instead of the one with family reunion

- Trigger an event that cause multiple NPCs to visit granny and makes her mood unstable
    - Can be triggered on purpose 来获取只有在unstable mood的时候可以获取的info/items/etc.
    - Can be a situation that needed to be solved by player

- Celebrate birthday for the Granny
    - Bring a gift to the granny
    - Arrange a birthday party for the granny with NPCs in the town
    Get the granny’s family members back

- Introduce the granny to twins👯 and get her confused
    - Player needs to discover the twins as twins
    - Twins have distinct personalities; Granny mis-recognized them and get unexpected conversations/interactions
    - One lives in the apartment and the other comes to visit
    - Depending on the granny’s mood, she may find the twins amusing or annoying

- 老年维权斗士相关故事线
    - User can interact with the ordering system in the restaurant - they can either add a random item the granny didn’t order in her check, or delete one (Timer: for this one, we could create a separate page that zoomed in to the screen of the ordering system, when the user clicked into the zoomed in page, the timer would stop, and they can take their time to choose whether to add, delete or keep the items )
        - Granny went to the restaurant by herself
            - Add item
                - Granny try to fight with the waiter
                - Receive negative comments from other customers
                - Decrease mood variables
            - Delete item
                - Granny pay less and become happier
        - Granny went to the restaurant with someone else
            - Add items
                - Granny fight with the waiter and helped friends to get the money back
                - Received positive comments from friends
                - Realized that she can still contribute in a social setting - increase mood variables
            - Delete items
                - Granny try to hide the fact that she did an unethical decision
                - Increase happiness but decrease her willingness to participate in social situations
    - Or swap the granny’s check with another table

## Storyline

### Task 0 (Tutorial)

### Task 1 (Demo) - Helping Granny find a lost item

- Lost Item: Medicine Box
- General Storyline: 
    - Granny lost the medicine box somewhere, and forgot that she even needed to take the medicine (occasionally flashes back to a younger self due to memory loss)
    - User trigger events that got the medicine box back to the granny in some way
    - Granny refused to take the medicine box, and got mad due to the fact that someone thinks she’s old and needs to take 5 different pills a day
        - If mood is average - Granny refuse to take the medicine box, and gets mad due to the fact that someone thinks she’s old and needs to take 5 different pills a day
            - Trigger another task [骗奶奶吃药]
        - If mood is high - Granny is grateful to have the medicine box back (or grateful to the NPC who delivers it back, and will take the pills peacefully)
        - If mood is low (maybe when the stress level is high and Granny becomes paranoid) - Granny believes that someone swapped her pills and wants to poison her
            - Trigger another task [investigating suspicious neighbours], player needs to help granny to investigate 3 suspects and prove their innocence
            - Granny will accept the pills after the task is completed

- Event Ideas:
    - Someone may bring a box of vitamins during their visit, and the user can add the vitamin into granny’s medicine box or trigger the NPC to add
    - Depending on different conditions (granny’s mood variables, what she memorizes, etc.), the granny may get mad at random unknown pills in her box (sooner or later!). She started wondering someone may want to kill her 
    - Users can also choose to put the vitamin bottle outside where the granny aways passes by. In this case, she’s happy about the vitamin cuz she’s able to read the label and understand what the pills are, but she will take it multiple times a day → generate health problems → decrease mood variables
    - The only way for the user to get around this issue is to put the vitamin bottle in the cabinet which the granny will only open once a day (e.g. the one that stores her coffee beans, etc.)

## Endings

### Main Concept:
Granny will pass away no matter what the player did 一种无力感
Format:
A line announcing the death of Granny (when/how/HE or BE)
然后像电影结尾滚动字幕一样a list of how player’s action affected Granny starting from day 1

两个主要结局走向及相关任务（可以达成多个）

- 玩家帮助奶奶完成过去的梦想和执念，所以她不再需要假想朋友 【核心：弥补遗憾，但可能会发现这只是玩家的执念，而非奶奶真正的需求】
    - 成为小镇广场舞领舞——但领舞最终不属于她
    玩家帮助奶奶成为领舞，但奶奶登台第一天，有一个更年轻的、有活力的奶奶从观众中站出来挑战她，用更炫酷的广场舞动作赢得了大家的目光。但玩家看见奶奶露出了释然的笑容，意识到奶奶真正想要的并不是成为‘第一’，而是享受舞蹈本身
    - 重温作为地质学家的成就
    - 完成关于爷爷的遗憾
    - 和家人重新联络

- 玩家关注奶奶当下的需求和新的愿望，奶奶发现当下的美好，逐渐忘记了玩家的存在 【核心：当奶奶找到新的目标和幸福，她对过去（包括假想朋友）的依赖会逐渐消失】
    - 和所有邻居成为朋友（玩家可以帮忙赶走坏邻居
    玩家努力帮助奶奶和邻居们改善关系，最终所有人都喜欢奶奶，甚至每天都来找她聊天。但当奶奶有了足够多的朋友后，玩家的行为对奶奶的status的影响越来越小
    ，她不再需要玩家。玩家被“冷落”后，开始像幽灵一样“恶作剧”，弄翻水杯、破坏物品，从而引起奶奶的注意，从一开始的帮助奶奶生活变成绕乱奶奶生活
    - 和小男孩谈恋爱
    - 找到新的爱好（比如打游戏)
        - 奶奶在她玩的游戏里创造了角色，这个虚拟角色似乎是奶奶新的假想朋友，而玩家已经变成了过去的、被遗忘的。然而某一天玩家发现奶奶无意识中在游戏里创造了一个和玩家自己长得一样的角色（前提是我们给玩家搞个画像），玩家意识到奶奶并没有忘记自己

当完成类别1里的任务大于类别2时，解锁结局：
- 奶奶死后玩家[通过某种方式]意识到自己帮错忙了，这些心愿并不是奶奶当下的心愿而是自己的执念，自己一直没有理解奶奶真正想要的是什么。真正被过去束缚的是玩家自己而不是奶奶

当完成类别2里的任务大于类别1时，解锁结局：
- 奶奶死后玩家可以选择和奶奶一起离开，也可以选择成为一个真实的人

结局彩蛋
- 奶奶死后玩家作为奶奶的假想朋友，可以选择和奶奶一起，也可以选择重生成为一个真实的人

Ending with Low Moods (FAIL)

Ending with high Moods (WIN)

## Algorithm

### Generally Interactive items
Most of the items outside or inside the house are interactive on a daily basis (or even multiple times a day for multiple players). They may simply generate an NPC reaction, trigger schedule changes, or [action item]. Events that can trigger schedule changes may vary in outcomes by the number of hours. Events that only cause reactions for certain NPCs may trigger schedule changes for others based on NPC personalities (for owned items, reactions only apply for NPCs who own/or use them, eg. coffee machine)
- Obstacles on their way to their destinations
    - Reaction + no schedule changes for NPC < 18 yrs old
    - 1 hour for granny (may differ by mood variables) + other NPCs except 👴
    - 2 hours for 👴
- (destroy) Coffee Machines
    - 1-hour schedule delay
- Drop books/items on the floor
    - Trigger reaction + no schedule changes when more than 3 items are dropped on the floor
    - Depending on items or if they have 洁癖, schedule changes may be triggered

### Schedules & Schedule delays
Each schedule item has hidden levels of importance. The event with the least importance will be skipped if schedule changes were triggered earlier in the day. Player can reveal these hidden details in the following ways (we may show these details on the NPC’s schedule if they are explored):
- By triggering schedule changes, and observing which items on their schedule were skipped
- By triggering NPC reactions and collecting information from their reactions
- Explore their house, find traces of evidence (doesn’t reveal details on schedule unless it’s something written)
- Explore the house of the newspaper guy or anyone who has 收藏癖
- By triggering NPC events and collecting information from conversations

### Plots/Conversations for Player-controlled NPC meetups
- Granny + NPC → trigger friendship reactions (either positive or negative)
- NPC + NPC → trigger gossip that may positively or negatively affect Granny (or some 密谋)
- 4+ ppl → trigger restaurant or party events
- (Meetup locations may change what will be triggered. This needs to be added after locations are finalized)

## Question List
- Too much information for the user to keep track of (timer base or no?)