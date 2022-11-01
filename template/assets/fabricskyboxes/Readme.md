__Readme FSB folder__

If you're converting an existing OF/mcpatcher sky pack, your sky type for FSB will be 
"square-textured" (like in the example _overworld_sky1.json_). For the schema-v2 docs 
have a look at https://github.com/AMereBagatelle/fabricskyboxes/blob/1.19.x-dev/docs/schema-v2.md

In the old Format, the textures are ordered like this:

1 2 3

4 5 6

1: bottom
2: top
3: south
4: west
5: north
6: east


If you're using FSB < 0.6.0, you need to rotate your TOP texture 90° clockwise!
