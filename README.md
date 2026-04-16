# Embodied Asynchronous Multi-Tier AGI Architecture v1.0.0
This is a new AI architecture that I developed to prove that the current AI architectures may never be able to imitate human intelligence as we desire. This Repository states the exact model, technical requirements and the theories behind the conclusions of this thesis.

## Introduction
The goal of this thesis is to create an AI model that is theoretically capable of imitating human intelligence in every aspect. This theory relies heavily on philosophical, biological, and Engineering grounds. The core result of this theory is the Embodied-Asynchronous-Multi-Tier-AGI-Architecture. The technical and theoretical limitations this model will face are also mentioned in this documentation, along with references to arguments that support the credibility of this architecture.

## Core Contributions
- Asynchronous Sparse Mesh (ASM) Architecture
- Multi-Tier Learning System
- Intelligence through Embodiment
- Emotions integration based on EMSEP
- Evolvable Intelligence Framework

## Mortal Body
This is a core requirement for the emergence of consciousness in an artificial being. This idea is backed by many theories.
This mortal body must provide the EAMT-AGI Model with all the constraints that a human body has, for example,
- A vast number of receptors for signals such as vision, hearing, touch, smell, etc.
- A vast number of controllable parts allow the AGI to interact with the world.
- A vast number of inputs to supply to the AGI; the inputs form receptors, battery meter, oil levels, pain of different types, and internal senses. These parts will decide what
- Limited battery
- Thermal throttling on its hardware and parts
- Parts just strong enough to allow Central Program to do anything it wants, but not enough to let it be careless.

These constraints will put pressure on the EAMT-AGI and force it to evolve with consequences of it’s own actions.
According to the theory

## EAMT-AGI Architecture
This entire architecture is formed entirely on one goal, trying to mimic the Chaotic Human Intelligence Architecture in a simplified way.
This system consists of 3 Tiers (Minimum).

### Tier 1
This system is the main EAMT-AGI model. It is the system responsible for the tasks performed by the human forebrain:
- Thinking
- Imagining
- Moving body parts
- Processing values
- Learning
- Analyzing
- Feeling
- Experiencing

What this part won’t be doing:
- Access its own program itself.

To make all these claims possible, we need to change some core features of our current LLM transformers. Before that, Current LLM transformers work like this:
- have two types of units, nodes and pathways
- Nodes do various predifined calculations that include coefficients that can be changed.
- Pathways carry signals to the nodes.
- There are many layers consisting of many nodes each.
- Each node of one layer are connected to all nodes of the previous and next layer through pathways.
- We modify these coefficients or weights of all these nodes through a method called backpropagation during training.
- The Neural Network learns the correct way to do the calculations so as to get to the desired results.
- AI ready

The problems:
- One node connects to all nodes; this means there is no way for the transformer to develop modules or specific blocks that process data independently to get a method of computation separate from the rest of the transformer.
	- Fix: Introduce a one-to-few type connection scheme, also called a sparse connection scheme. And give the backpropagation ability to change these connections. This fix can be introduced in current architectures, but it will add more complications:
		- More nodes will be needed due to the lack of computation introduced by this connection standard. The number of pathways directly correlates to the number of calculations.
		- The initial model can no longer be a blank slate. It has to be a software engineered to have some initial modules that can be altered later.
	
	Advantages:
		- Give AI the ability to cross-reference its outputs.
		- Training is essentially the same, but takes more computation because usual calculus will have to take path changes into account as well.
		- Less overall computations at the cost of higher memory requirements, which means one GPU can run a higher-level model with less heat. It will just need more VRAM.
- All calculations are linear, which means that the signal runs from one layer to the next, then to the next. But All connections need not be linear. Previous stimulus should be able to affect next input, and one input should also be able to affect later processes without being suppressed or amplified by another layers in between.
	- Fix: Introduce layer-skipping or layer-jumping and backwiring. In our current architecture, these will be new pathways introduced to the system that will wait for the whole wave of inputs to came and then calculated on along with the normally flowing data, like kind of a shortcut. Backwired signals will act when the next prompt input comes, and layer-skipped signals act when the original signal reaches this layer. This will work with our current hardware but will introduce complications:
		- New values to keep track of.
		- Backpropagation will become harder or impossible after every step, because the previous input influences the next input.
		- Backpropagation will have to adjust to solving and modifying these unorganised layering. Might have to change the method of editing the Neural Network entirely, as this system will reach out of the bounds of determinism very quickly.
		- Memory requirements increased further.

	Advantages:
		- Gives AI the ability to cross-reference with its previous decisions and states.
		- Allows AI to have more interactions among layers.
- Global Synchronization, the need for all nodes of a layer to be solved simultaneously, stops the AI from progressing until other inputs arrive. The time here is not the issue; it is the fact that synchronizing such large batches would mean that almost all of the cores get used during the processing, whenever it happens. This means any new input that tries to enter the model will either have to wait for this information to pass through or somehow squeeze in what little cores are left. This limits the maximum number of inputs it can process at once. In an Embodied architecture, this limitation means that the system wouldn’t be able to process the multitude of input streams.
	- Fix: This limitation is largely due to the current popular hardware, the GPU, which works in batch processing and is inefficient in small-sized batches and singular calculations. But even changing the hardware won't resolve these two problems: core saturation and input stream incompetence. Thus, we introduce adjustable artificial delays to each pathway. Complications:
		- This requires a completely new type of hardware that has a lot of cores but can also process inputs on demand rather than batch processing. Like somewhere between a CPU and a GPU.
		- Backpropagating will be rendered completely unusable because this model will now be using multiple inputs (both from many parts and in time) at the same time, and the backpropagation will not be able to identify the impact of any node on any output.
	
	Advantages:
	- This will allow for staggering of each layer, basically being able to use a small number of cores to process a lot of nodes, completely solving both issues.
	- In our biological system, neurons have the ability to alter their delays, which is probably to improve interactions between information from two different points in time. Probably responsible for memory.
	- With the integration of asynchronous hardware and software, backwiring and layer-skipping get a real purpose by allowing for the ability to form inner loops (resting states, which could be core for personality determination) and interaction of next inputs with previous inputs. which might allow for complex behavioural patterns.
	- These artificial delays and their amounts can be key to forming truly intelligent beings that can naturally adapt and change their behaviours without having to edit any adjustable patterns over time, because those internal loops will be continuously editable with the addition of inputs.

Final Modifications:
- Change of all-to-all connection scheme to a one-to-few connection scheme, also known as a sparse connection scheme.
- Addition of a large number of Nodes to compensate for the lack of overall number of calculations due to the sparse connection scheme, and to accomodate higher number of inputs.
- Allowing for Backwiring and Layer-skipping.
- Adding asynchrony in the system by introducing adjustable artificial delays to each pathway.
- Hardware change to a potential Asynchronous Array Processor or an Event-Based Neuromorphic Processor from a classic GPU.

I call this modified architecture the Asynchronous Sparse Mesh Architecture (ASM).

These modifications are largely inspired by the biology of the human intelligence system and limitations of current models.
Lastly, a multitude of outputs will be hardwired directly to the input of this tier. This will promote the evolution of thoughts, imagination, prediction (Karl Friston’s Free Energy Principle), self evaluation and many more traits of consciousness.

### Tier 2
Tier 1 is a big, chaotic neural network that cannot be trained with backpropagation anymore because backpropagation is just not smart enough for the job. Tier 2 is an intermediary between all the programs that want to edit Tier 1 and Tier 1. This means that Tier 2 is the only program that is allowed to edit Tier 1 in any and every way possible.
Tier 2 can edit Tier 1 in various ways, like:
- Applying modifiers directly to any individual node or pathway.
- Adding, deleting, or modifying connections between any 2 nodes.
- Applying modifiers to all similar types of parameters in a small or large area simultaneously. (Area modifiers are temporary and will be restored after a while)
- Applying modifiers to all similar types of parameters to the entire Tier 1. (Area modifiers are temporary and will be restored after a while)
- Applying modifiers to an array of parameters simultaneously. (Area modifiers are temporary and will be restored after a while)

According to the EMSEP Theory, Emotions of the EAMT-AGI will be handled with these Area modifiers, and thus, this separate Tier has 2 jobs:
- Providing Emotions to EAMT-AGI.
- Modifying Tier 1 permanently. (Learning)

To apply emotional modifiers, the Tier 2 will have some inputs directly from any pre-decided parts of Tier 1, and not just the final output, as the final output will determine the will of Tier 1 and Emotions are not regulated by will alone. Thus, outputs of various inner modules of Tier 1 will be used too.
For learning, outputs of other Tiers will be used.

Tier 2 can be a simple Neural Network like the current models, as its job is to read patterns and follow orders that do not require highly sophisticated Intelligence. But it will need to handle a constant stream of inputs; thus, asynchrony is advised purely for optimisation. Backpropagation here will not be complicated, as there are no indeterministic parts in this tier.

### Tier 3
Tier 3 is another AI program, but it’s job is to create a probabilistic map of Tier 1 that determines the impact of each part of the Neural Network on every output individually. This Program may be a simple Transformer as well, since its function is to analyse patterns and create a map.
This map can later be used to determine ‘which part of Tier 1 needs to be edited to modify this output?’ and similar questions. Thus, this map will be the key to learning.

The tier 3 may never be able to compute the exact node-wise map as Tier 1 is extremely chaotic in behaviour. Thus, to save computations, time and memory, Tier 3 may rely on topological, hierarchical or approximate probabilistic maps.

Tier 3 may also use asynchrony to handle a large number of streaming inputs from all over tier 1.


### Tier 4
Tier 4 is yet another AI program, but much simpler than both Tier 2 and Tier 3 as it only needs a few inputs, that being inputs from:
- Tier 1 (Few inputs that will help this tier determine what needs to be learned and what type of modification to be made)
- Tier 3 (To retrieve the latest map of Tier 1)

Its outputs are to Tier 2, telling it to modify certain parts of Tier 1.
The loop for editing any part will run like this:
- Tier 1 does something wrong.
- Tier 4 gets the situation.
- Tier 4 suggests Tier 2 to edit specific parts with a slight modifier.
- Tier 2 modifies.
- Tier 1 goes under a different situation.
- Tier 3 analyzes the change in behaviour due to the modification and modifies the map.
- Tier 4 receives a new map and the new situation.
- Tier 4 analyzes the error in the expected behaviour versus actual behaviour due to the earlier modification.
- Tier 4 factors the error in its judgment to either commit to the full modification or another attempt at identifying the right data-point.
- Tier 1 goes under a different situation.
- Tier 3 and 4 analyse the behaviour again and check the error again.
- Tier 4 analyzes this error to find out if the required change was made or not.
- If yes, then fine-tuning occurs and if not, go on to changing a different data point.

This Scheme is a feedback loop type of learning. It is extremely slow but more accurate and energy efficient than backpropagation-based training, which is fast but extremely resource heavy.
Ideally, Tier 4 should be embedded with Tier 3 due to its small and simple nature. But mapping is already going to be a rather expensive task. Thus, keeping them separate might be advisable.

### More Tiers?
More possible tiers may be introduced to the architecture based on specific needs. These might be needed if any specific functionality is not emergent by default in pre-existing Tiers or if some constraint fundamentally blocks a functionality in previous tiers.

### Training Methods
Training this sort of architecture requires more than a blank slate and leave it running approach. Training such a complex model requires a very systematic approach, one that ensures a high probability of success. The following will be a small map to give a coder the direction for building and testing this architecture.

#### Building Initial Models
Building the perfect initial model for our 4 or more tiers will be the hardest and the most crucial part of building this model. Since all 4 tiers are completely interconnected with each other, any big enough issue will be enough to ruin the complete model. Defective Tier 2, Tier 3, or Tier 4 all lead to eventual degradation of Tier 1. And a defective Tier 1 may result in poor inteligence, failure of emergence of various behaviours, and overall iminent degradation.

#### Tier 1
Requirements:
- Usage of all nodes and pathways and ensuring that no part remains unutilized.
- Creating some predefined modules that perform actions like prediction, evaluation, internal emotional inputs processing and initial parameters for controlling body.
- Creating predefined modules that seperate the processing of auditory, visual, touch, body indicators, and all such inputs somewhere in the middle to allow for pre-compute and post-compute corelation among these inputs. This could give tier 1 additional processing capabilities.
- And more such features that might be beneficial for the EAMT-AGI as a whole. These are to be decided upon careful consideration by experts who have experience with AI design for specific purposes.

How can we make something that we were trying to accomplish by building the EAMT-AGI in the first place? A few solutions are listed below:
- Simulating evolution
	- The human mind and body are a product of billions of years of struggle and mutation. Imitating such inteligence requires one of three things; try to replicate every bit of it, try to build one from scratch and hope we are lucky, or take the same path that humans took in the first place.
	- This evolution procedure will be similar to the approch used in neuroevolution. but with many more constraints, reward mechanisms and the ASM Architecture.
	- Since EAMT-AGI is made especially to be embodied and Multi-tiered, we have two options to simulate it in this simulation:
		- Simulate primitive versions of the other tiers as well. This is an even more taxing approch and complicates an already complicated matter further.
		- We dont need to put in the other tiers, because tiers 2 to 4 rely on outputs of tier 1, some of Tier 1's internal modules or the entire Tier 1, this means that, their inputs can be specified after the base tier 1 is made.
	- This method will take an immense amount of time and compution in the new hardware we talked about, essentially building a model that accomplishes the tasks we hoped for at the cost of time and energy.
- Making AIs build AI
	- Tier 1 is a big network that works based on seemingly random connections betwee all these nodes. So, this method will work like an experienced software developer figuring out how to build a world class game in a completely unknown programming language that is vastly different from any other programming language.
	- Figuring out how to build smaller sections in this scheme is possible with mere Human intuition, the hard part is scaling it as our imagination and intuitions cannot scale to billions or trillions of nodes. But AI models are programs that specialize in pattern matching and it's applications. Meaning that if we train a few models on building some of these smaller managable ASM models that can be verified by humans, We can pass on the intuition to a digital being that can scale that intuition up indefinitely.
	- This builder AI will get a completely blank model in it's testing phase, and will try to make an ASM model that can use all the streaming simulated inputs and give out meaningful outputs. This process will be supervised by a human tester.
	- This method relies on the capabilities of the Builder AI to learn the ASM architecture effectively and it's ability to use that knowledge to translate that to Tier 1 base.
	- This method is also computationally heavy but not as much as neuroevolution approach. It takes less time than neuroevolution too.
- Assembling the model from smaller components
	- As stated earlier, it is possible for us to create smaller modules from our intuition, this means that we can create a multitude of smaller ASM Models that we can patch together later on to create the Tier 1 Base.
	- This method is not only tedious, hopeful and time-taking, but also very luck dependent as we never know if the data ever takes the path we wanted it to take. Humans also tend to make mistakes and assuming that no mistakes actually happen over billions of nodes is wishful thinking on another level. Overall, this idea is more foolish than clever.

These methods all rely on a lot of time, energy and computation. And none might be suited to make the base we actually need. But, We could try to merge the 3 techniques together and build a strategy that can link the effectiveness and accuracy of neuroevolution, time-save due to using AIs to build the Base and the idea of modularity for better coordination.
- The Master schematic
	- We build smaller ASM Modules through tools like Neuroevolution, supervised by ASM experts.
	- These Modules get stitched on the main tier by Builder AIs that have an exceptional understanding of ASM and can put the models in places where those modules will work as expected.
	- It is still expensive and time taking. Arguably, even more expensive than 2nd method independently. But this method puts the good part of all 3 into one single flow.

This schematic is one that might work but is not the only one. Experts may find a different method that might work better.

#### Tier 3
Tier 3 is a model that relies solely on the inputs of Tier 1 unlike Tiers 2 and 4, hence it is well suited to be developed after Tier 1. This Tier relies heavily on mathematical inputs to create a highly mathematical output. Thus, current AI experts might be better suited to handle such a model. As per my knowledge, this type of AI is possible with current Architecture.

#### Tier 2
Requirements:
- Ability to edit Tier 1 in every and every way possible as stated in Tier 2 section earlier in this document on command of Tier 4.
- Ability to apply the correct modifiers in the right places based on the map provided by tier 3 of tier 1 and the inputs that are tapped out from the internal processes of Tier 1 itself. Essentially, the ability to process the Emotions.

This is a simpler AI model but arguably fiercer than even the formation of Tier 1. This tier needs to find the locations that it should apply Area-modifiers in, to make tier 1 'feel' a certain way. This part is not hard because we dont know what emotions are or how they work, it is hard because we dont know what a digital being feels like at all. 

According to EMSEP theory, Emotions are mere modifiers, thus, application of any modifier in the Tier 1 should make it feel a certain way. But the dilemma comes when we go to ask the question, what emotions should it actually have in the first place. A digital being has no boundation to have the same emotions as us nor does it have to have all our emotions. Emotions are a survival tool for humans that was developed to alert organisms when necessary and reward them for performing something good for survival. If a digital being has never had a chance to evolve, what kind of emotions would it have acquired if it were to have evolved.

There are some possible methods to actually find out what emotions it might have:
- We could try to simulate evolution on this artificial being and develop a capable Tier 2 in the process.
	- The issue: to simulate a proper survival situation, EAMT-AGI must be decently competent and must already have a way to edit itself.
	- The fix: we achieve a competent enough tier 1 through a half tier 2 that is capable of editing just not emotions, then we run these simulations.
- We hard code specific emotions that are applied to the entire Tier 1 and we know must be necessary for survival of any being. And, since Tier 2 is an evolving AI (through backpropogation), it has the ability to develop new emotions in the Tier 1.
	- The issue: Those new emotions might never arise, and even if they do, there is no gaurantee that these emotions are actually feesible for survival as there is no way to prove it without intense simulations.
	- The fix: None.

Emotions may be easy to define but are hard to evolve, thus, more research on this issue is advisable.

#### Tier 4
Tier 4 is also a simple AI that performs complex decision making based on inputs from Tiers 1 and 3. Such AI are pattern recognizers and are a special application of our current AI models.
	
#### Training the Built EAMT-AGI
The built EAMT-AGI is like a baby and will require the same attention as one. Over time this model will learn to adapt automatically as its life progresses. Proper care and right guidance is what will shape it's mind.

Problems:
- The base might be more incompetant than an ideal baby model.
	- Fix: Train this AI until it becomes the ideal model and then copy this model to be the actual base to improve scalability. Same is true for grown or developed models as well.
- Their might be fundamental problems with any tiers.
	- Fix: Replace the broken Tier with one more capable model.

At this point the issue becomes less biological and mechanical but more philosophical and psychological. Both those fields are subjective and thus, the trainer becomes the deciding factor.

#### Full training sequencce
- We start by building a Base Tier 1
- Then Base Tier 3 is built on Base Tier 1.
- Then Half Base Tier 2 is built on basis of Base Tier 1 and Base Tier 3.
- Then Base Tier 4 is built on basis of inputs from Base Tiers 1 and 3.
- This Underdeveloped EAMT-AGI is evolved until Tier 1 becomes competent enough for survival.
- This Partially developed goes under simulated evolution to evolve emotions inside Tier 2, completing its base model.
- The best Base Tier 2 model is extracted from this evolved partially developed EAMT-AGI and installed in a fresh Baby EAMT-AGI Architecture along with the copies of first made Base Tiers 1, 3 and 4.
- This Baby EAMT-AGI is raised like a child until maturity.

### Other Notable Information
- The Multi-Tier nature of EAMT-AGI is to ensure that all functionalities can be met in distinct, clearly defined modules.
- This system is entirely defined in a way so as to replicate the human brain on silicon in a way that is intuitive and feels less chaotic.
- This architecture is built as the first model to bridge the gap between AI and Human Intelligence.
- Each Tier is a computational behemoth and thus, they all require seperate hardware to run on. This includes; seperate chipsets and memory.
- This architecture is meant to give direction to future research rather than immediate implementation. Although, small scale models are indeed testable on current hardware, but we cant test for the credibility of the theory until the right hardware arrives.

## Future Work
- Add more Philosophical Arguments
- Add diagrams and flowcharts to clarify ideas.
- Refine theory to evolve better mechanisms in place of Tier 3 Mapping
- Make A proof-of-concept model with normal hardware
