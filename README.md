# This repo contains accomplished projects using Python NetworkX library
1) Mid-term group project focused on IMDB actors network
2) Individual Final course project analyzing the sentiment diffusion phenomena on traders network

## 1) Dscription of the Mid-Term project

1. Scrape the IMDB website to build and build a network model 

2. to identify the relationhsip(s) included in the selected network dataset and
to appreciate the economic, organizational, managerial, and/or social relevance
of the relationship(s)

3. to use Python:
   1. to analyze and plot the degree distribution of the network
   2. to plot the network
   3. to produce descriptive statistics about relevant node-level properties 
      (e.g., betweeness centrality)
   4. to asssess how and to what extent the network shows a modular structure
      (e.g., a community or core-periphery structure)
   5. to assess the consequences of the modular structure for 
      the individual nodes, the individual communities, and/or the functioning
      of the network. For example, one may want to correlate the network position of an individual (core Vs. periphery) with her attitudes, behavior, preferences.

4. to produce a companion document that — in plain English — describes and
comments  the outcome of the previous point 3.i - 3.v. 

## 2) Final Course Project background

The compound of technologies we use to call 'AI' promises to revolutionize many
sectors. However, there is a substantial gap between what firms say they do with
AI and what they actually do with it [1].  Several factors could account for
such a gap: the adoption of AI tools is costly since it tends to jeopardize an
incumbent's operations [2]; there is a shortage of human capital trained in the
area of AI [3]; developing AI applcations may require businesses to cope with
ethical/societal implications [4, 5] and regulatory issues [6]. In the context
of knowledge intensive industries, there is yet another obstacle to the
diffusion of AI, namely, 'professionals.' While some individuals may be
thrilled to integrate AI in their daily work, some others may just feel
threatened. This FCP deals with the distribution of security traders opinions
about the impact AI can make on 'trading floors.'

## Aim & context

You're a 'quant' business analyst working for a consultancy company that has to
help a client to sustain the diffusion of AI. Specifically, the client is a 
large investment bank that would like to persuade traders to engage more with
AI tools when it comes evaluating securities.

## Dataset

In order to get a better understanding of traders' attitudes toward AI, you have
circulated a survey in a large trading floor located in Canary Wharf. The
resulting dataset ([trading_floor.xml][dataset]) contains 192 responses
regarding:

- the undirected network of knowledge exchange between traders (traders A and B
  are connected when A says he/she shares technical and industry knowledge
  with B and _vice versa_)
- a trader's opinion about the contribution of AI to his/her productivity and 
  effectiveness in evaluating securities (1 = not at all; 10 = to a great 
  extent). In the datasets, this variable is reported as the node attribute `ai`.

Thanks to the cooperation of the client, you also know the traders' location
in the floor. There are six zones, each of which hosts 32 individuals (16 
individuals on each side of the zone). The above-displayed picture gives
you an idea of the layout of the trading floor. In the dataset, the location
of traders is reported as two node attributes, that is, `x-pos` and `y-pos`.

## Questions

1. How do traders' opinions map onto the knowledge exchange network?
2. How do traders' opinions map onto the physical layout of the trading floor?
3. What are the network-related obstacles to the diffusion of positive 
   opinions about AI in the trading floor?
4. What is your recommendation to promote the diffusion of positive opinions
   about AI in the trading floor?

