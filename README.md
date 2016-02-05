# Tasks

# key
* trigger: what starts the task, usually events
* location: where the task starts
* priority: high, normal, low

## Clean Inventory
* prirority: high
* trigger: user made task was finished
* location: user defined junk drop-off point (can be an trash can or a sorting system input)
* removes items from the turtle which don't belong

## Refuel
* priority: high
* location: user defined fuel collection point
* restocks fuel if low
 
## Building Farm
* priority: low
* trigger: on user in put
* location: assined by user 
* run on of the many farm building programs which needs Dir and size.


## Harvesting Farm
* priority: normal
* trigger: by user or automatic recycle
* location: farming station
* does one harvesting cycle on farm

## Mining 
* priority: low
* trigger: by user or automatic recycle
* location: starts from bedrock and works up
* mines until inventory is full or if it has enderchest until job finished
