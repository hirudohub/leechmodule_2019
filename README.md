# leechmodule_2019
Data and Code Repository for the NS&amp;B Leech Module, c/o 2019
The medicinal leech, Hirudo medicinalis, is an important experimental preparation in neuroscience, contributing many insights into how nervous systems produce behaviors, including rhythmic behaviors such as swimming and heartbeat and behavioral choice [1,2]. It is also well-suited for neuroscience education. There are several reasons for this:
1.    Neural circuits in the leech have been identified for several behaviors, so they can be studied rigorously, from sensory input to motor output
2.    There are enough neurons (~10,000) to form complex neural circuits, but not so many that single neurouns cannot still affect behaviors
3.    The neurons are large and readily recordable, using multiple techniques (intracellular, extracellular, voltage-sensitive dyes, etc.)
4.    The neurons are also easily identifiable, occupying stereotyped locations within the segmental ganglia of the leech. This identifiability extends across animals, so reliable recordings of the same neuron can be made in multiple animals
5.    Behaviors in the animal are robust, allowing for behavioral assays in both intact and semi-intact preparations

Finally, over the years, there have been numerous courses devoted to understanding the neurobiology of the leech, including one at Cold Spring Harbor Laboratory (Neurobiology of the Leech.)
About this Data
The historic Neural Systems & Behavior course (NS&B) at Marine Biological Laboratory in Woods Hole, Massachusetts begins each summer with a module on leech neurophysiology. The NS&B class of 2018 has kindly shared a library of their leech electrophysiology data, to enable future students and researchers to explore and learn from their data. These data include both the raw intracellular and extracellular recordings, as well as some pre-computed analyses (spike detection, spike sorting).
About this Example
This example illustrates the exploration and analysis of a single bout of (fictive) mating behavior in the leech. Interestingly, although crawling is a whole-body behavior, many aspects of the fictive motor pattern can be elicited within a single ganglion, making it an ideal testbed for how nervous systems produce behaviors [3]. It illustrates the computation of various electrophysiological measures such as the inter-spike interval (ISI) and instantaneous firing rate (IFR), and how they can be used and even further quantified (e.g. Fano factor analysis) to characterize and compare neural activity.

How to use this example:
Download the 1ex1insigvolt.mat file and the 1ex1insigtmsspks.mat file. These files contain the following:
1ex1insigvolt.mat: The raw voltage traces used for the analysis. There are two channels in this record
1ex1insigtmsspks.mat: The time vector for the voltage traces as well as a structure of the spike times
