# MyBlenderAddons
a collection of my blender addons made with Serpens3


## Fast Collection Rename
will add a button in the outliner > Collection Context menu

![Collection_context](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/ac813de5-f0da-4f4a-9336-ae437d615a0c)

if pressed, you will get 3 or 6 entrys which you can choose from

![presets](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/a8c69bb8-b088-409e-901b-f5b404dfba4b)


## Sloped Surface maker
this one is one of my first addons i made, bugs included ;P

![Panel](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/f6e5cb59-343b-40e1-8109-a45c86bafeab)

select two "mesh curves"
one oriented along the X axis
the other one oriented along the Y axis

![from](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/bab9589b-2691-4f3b-b495-beb29a7ca251)

it will instance object X on each vertex from object Y and the other way around.
the ressult on this example will look like this:

![to](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/1172ee03-78e0-4da5-918e-200f7e85578e)


## Batch material replacer

accesable in Object Context menu

![menu](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/3b9f09ea-0453-4b1d-972c-0c2e6ec6e5f9)

will open a pannel that lists all materials from all selected objects

![Screenshot_1](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/aa6c255e-6977-458d-af31-c6abeb44e4a0)

after selecting the material you want to replace another panel opens, (shows all materials from "Blender File/Materials") wehre you select the material you want to insert

![Screenshot_2](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/adf1625c-1b57-44c2-909f-d74462c69e77)

Result for all selected Objects:

![Screenshot_3](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/eaeebc2c-6244-416c-b1a9-19b383fe556b)

# copy paste vertex Z
allows you to copy the Z value from a vertex and paste it to multible vertices

Example:

![before](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/d28578f8-8b83-44e0-a381-c803142097af) ![action](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/038176bd-ca0b-40ef-9c82-fe618c4a137e) ![after](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/a2a4f8f3-b595-4759-916b-966450e7cbe6)


# material 001 be gone
it tryes to replace "material.001" with "material" but if "material" does not exists in bpy.data.materials the it shows a big error message LUL

![before](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/72476424-a1ce-4d12-b9ba-a678b0285987) ![result](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/17b69d48-5d28-4509-a122-174e9a7e90d8)


# Z deform
a very complex and not jet finished (work in progress) addon.

![panel](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/31e93683-78f2-4f1b-a1cb-3d8e85f450aa)

From this:

![from](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/8eea1f98-d753-4ca5-a59b-b995895a4211)

to this:

![to](https://github.com/StupsKiesel/MyBlenderAddons/assets/43930570/155bf013-d698-40c8-9220-901910c16010)

# 3D View Settings

because i get allways anoyed when opening blender when the view settings will hide all the mesh objects. this litle addon changes the settings on every instance you load into blender. you can customize the values in the prefferences panel.

# Operator: select_more_alt

This one is an altered version of [ STRG + NMPAD_+ ]. By also holding the "ALT" key. it sellects more but if it enconters an angle change between faces that is bigger then 45° it will not sellect the faces.
