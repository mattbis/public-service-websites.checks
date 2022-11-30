# public-service-websites.checks
.. this is how to make your website accessible to everyone and follow a standard set of rules.. that mean it works forever. 

1. lets formalise last nights brain storm and fix the names.. into how it should work even now in 2022.
- lets ensure you do not waste money on terrible implementations
- lets provide an experience that works from the slowest connection to the fastest. and uses the minimal amount of javascript. and web technologies.

# organisation

## particular case studies

- charities
- simple business service
- petitions
- social interaction

### example use cases

### modifiers of website
- orientation
- global
- local
- regional
- trust
- archive
- structure
- mapping
- formats
- history
- syndication
- updates
- indexers
- social media
- free media
- open media
- data formats
- data types
- service types
- application types and maps - this concerns a scale from a basic static to some restful / graphql service
- monitoring and insight
- code feedback
- user feedback
- vip

### aims 

#### ratings see trust
- noble, gov, fellows, security, civil, education, bodies, orgs, companies and syndicators

#### usability
- global attributes
- global artefact
- hateoas
- micronav
- microdata
- static
  - nav renders / reader pages
    ( this is what i described before it means you can find some category or petition for example and ask /nav this means you then get a page that indexers use ( considering you setup you links and alias from canons to actual content ) - the types of pages serve as landers or indexers for next and prev, and up or down and also in or out... they dont need to be in the app.. their purpose to aide readers and crawlers 
- progressive minimal enhancement 
- progressive enhancement
- a1lly
- pa111ly
- data sharing
- data description
- historical, posterity, duty, validation
- security
- scaling
- global | local
- feedback / insight and problems

## volume & scale 
- expectations
- automations
- trolling
- mistaken cases

## semantic aspirations
- none of what we have is particularly good...most of the web is bad...

## versioning and ..
- over versions
- under versions
- the need for versions
### data requires a clear taxonomy and organisation
- confusing people wastes countless hours in emails and requests - if you insist on providing API, then please, reorganise it via aliases, into something that actually makes sense : over the duration of the service.. and don't mothball stuff that is badly understood...
- if your cloud/service/node serves, it must be documented and it must be within a tree....

#### tree structure is all you need.

### critique and good
- aim of the website
- implementations and goals
- indexers, level of traction, need for standard
- react is not the solution
- server side react is expensive
- react is good
- react is bad 
- non react
- components are good but then they dont really follow any common form.. 
- hoc might have been good but then people dont like it
- now we have a mess
- software is always based on blocks that append to the outcome.. 
- simple frontends
- simple static systems
- bad cms
- bad enterprise
- basics
- community
- ui design and friendliness
- petitions
- charities
- services
- components - over generalisation - product creep - and control
- technology and product
- product and project management
- ui - over trusting designers
- ui - product problems
- ui - architecture
- ui - over simplification
- ui - gradual complexity
- ui - functional navigation
- ui - modes
- ui - navigation disasters
- ui - misleading pathways
- ui - maps
- ui - index
- ui - nav data
- ui - values and fields
- ui - sub hero fields
- ui - key data - and values 
- ui - colour blindness
- ui - themes
- ui - blandness - another black and white website
- ui - icons
- ui - image
- ui - figures and charts
- ui - css
- ui - css - performance optimisation
- ui - stutor
- ui - scrolling 
- ui - over design
- ui - under design
- ui - over product managed
- ui - cute
- ui - trust building

# motives
- ,,

# content

## referencing content
## describing content
## creating metadata
### cleaning metadata

## links

1. the first thing you have to consider, is every action of the internet is forever... every single link. 
- therefore its important to know in a sequential index, every possible end point on your websites graph... ( this is really vitally important )
  - **that you ever published** ... if it fails it will cause problematic traffic... 

2. with this in mind all urls must conform, and you shuld not rush how you publish them... in fact it better to ensure you can proxy a url via its canonical to several forms. ( transparently to link or to keep the canonical updated within the routing mechanism... )

3. so long as this exists in various sitemaps ( which should be compressed ) it will work... 
  - google-market-map
  - sitemap - all links - current
  - url-index --> url-immutable-index
  - sitemap.legacy
  - sitemap.alias
  - sitemap.images
  - sitemap.assets
  - sitemap.mobile
  - sitemap.shop
  - sitemap.nav
  - sitemap.tags
  - sitemap.meta
  - sitemap.org
  - sitemap.dyn-rating

a. if you change it dont forget what existed before this is the biggest mistake I see.. in fact this is what the `url-immutable-index` is... 

i. hash url
ii. denominator url

- sync with shorteners

#### routing map
### consistency
### check-links
### redirects
### validators
#### hosting / cloud / cdn 

# data
### formats
#### delayed cdn techniques
#### expected service
#### prioritisation

# trust / concerns
- how to gain trust... 
  - validators
  - virustotal
  - performance
  - standards w3c
  - security
  - sessions
  - certificates
  - references
  - key people
  - data retention
  - clear data policy
  - ethics
  - slave statement
  - carbon neutrality
  - mission statement
  - simple staff description
  - advert syndication and implementation
  - advert policy
  - funding statement
  - advert reason document
  - board mission statement
  - board composition
### do not present too much information
#### do not give away personal details - just enough for people to know what this is actually about 
- and you have nothing to hide.. 

# architecture

- domains
  - basic things
    - disallow email forwarding
  - aliases
  - dns services
- web buckets
- concurrency
- hashes
- url-immutable-index
- history
- formats
- cdn
  - options comm / free / social
- future technology web3 / peer web / peer tech
- rate
  - policies
    - overheads
    - ref: prioritisation and what actually is important

# security
- accounts and storing data mean instant problems
- admin enhancement ( please stop putting it in your main build since you are not very good )
- expand, since obviously this is specialised and a bit outta reaches eventually in document.

### mitigations and preventions
- using services & purchasing the right product.. do you really know how good this is .. does it do any of this? what is the point of being an ORG... 
- secret linting
- code linting
- cloud linting ( ? hmm )

#### IAC can become stale and untouched from a system that cannot be updated
- this is a massive problem... this is why versions, and double domains are a must... ( backup to preprod ) 
- do not become another org that never fixes costly mistakes in IAC and what the machines are actually doing...
- carbon neutrality.. 

#### common mistakes in envs
- have a preprod - when you syndicate to google and other indexers, you need to get it right .. etc.. it doesnt even need to be up always.. but a very useful testing ground.
- this will also validate perf testing without hitting the main copy

#### common mistakes
- robots.txt
- ex employees
- ex campaigns
- keys in code
- ancient keys
- rate limiting
- content length
- protocols
  - quik, http2/3
  - headers
- letting everyone have the secrets on their machines
  - **letting contractors know all your keys** - out of scope / blanket roles and users
  - use a vault
  - refresh keys via automation
  - do not add - agencies and internal people to cloud accounts
  - restrict agencies and internal to a seperate test env 
  - retain personell to manage rights, keys, transfer of code to production
- ** DO NOT ALLOW PEOPLE ACCESS TO YOUR PRODUCTION DATABASE ** WITHOUT GOOD REASON.
  1. even teh CTO can only see the replica
  2. CTO can see prod db in cloud, and subordinates
  3. retain strict access controls
  - ....
- verify ips within trusted zone - dont assume an ip is trustworthy for the entire duration of your company.. solid in IAC and forgotten ,, this is a terrible idea.


# navigation
  - functional
  - robotic
  - static
  - readers
  - accessibility
  - trawlers
  - crawlers
  - unofficial static links
  - fancy
  - mega-menus
  - paths
  - journeys
  - abstract techniques
  - visual techniques
  - deliberate obfuscation techniques
  - breadcrumb
    - disasters
    - variations
## the need for underlying static navigation cases

# ui
## journeys
#### use cases
##### petition
## page structure
### page html
### cheap html
## solutions
- base layer
- universal base layer

# implementation
### specification
### timescale
### base & iterations
### bottlenecks and architecture in the wrong hands... 
### being bold and making a statement
#### being aware of needs of all people
## kanban really works 
### being honest
#### people will like being told the truth
## gradual implementation from a solid foundation

# decisions
- choosing what agency to use
- stop making really bad risk and assumptions and focus on a clean and beautiful simple website... and not what your sold..
- please learn what cross referencing is ...
- dont think you need a super service like massive companies... you dont... since if that means your getting the **basics wrong** what is the point?
### business logic and the input of stake holders
- it is not productive to do something that has no logic behind it ...

# maps
## formal types
- linkmap
- sitemaps
  - advanced sitemaps
- datamaps
- resourcemaps
### descriptor types
#### xml
#### json
#### application/service
#### enhancers

## map --> graph --> rest / graphql / static / format
### graph edges
### nodes

## static descriptor
## dynamic descriptor

## tags
- over tags
- under tags
- using tags to reference the websites graph, map, and age
### local
#### global

# tools
# generators
# abstract examples

# organisation-to-donate
- archive.org
- ... 
