# Koalas to the Max 3D

A 3D demo inspired by the classic [Koalas to the Max](http://www.koalastothemax.com/). Subdivide a single voxel into a detailed voxelized glTF model. Built using [three.js](https://threejs.org/).

<!-- html video tag -->
<video style="max-height: 300px" width="auto" controls muted autoplay loop>
  <source src="./video.mp4" type="video/mp4">
  </video>

## Custom Models 
Better support for custom models coming soon. If you download the code, you can load in own glTF model by replacing the `koala.glb` file in the `models` folder. You will also need to change the `modelPath` variable in `index.js` to point to your model:

```const modelPath = './models/your-model.glb';```

Lastly, you will also have to [start a local server] (https://gist.github.com/jgravois/5e73b56fa7756fd00b89)

Check out [Poly] (https://poly.pizza/) for some free glTF models.

## Future Work
- Add in an upload tab for custom models
- Add in more default models options and the ability to switch between them
- Improve performance by using a improving the subdivision logic
- Improve performance by using a more efficient voxelization algorithm
- Improve 'out of the box' quality for custom models by using a better voxelization algorithm

I welcome contributions to this project! Feel free to submit pull requests or open issues.

## Credits
- [Koala](https://poly.pizza/m/9x4UY7n27nI) by [jeremy](https://poly.pizza/u/jeremy) [[CC-BY](https://creativecommons.org/licenses/by/3.0/)] via Poly Pizza 

- [Bonsai] (https://poly.pizza/m/44XK5UHTd4Q) by [Don Carson](https://poly.pizza/u/Don%20Carson) [[CC-BY](https://creativecommons.org/licenses/by/3.0/)] via Poly Pizza

## License
[MIT](LICENSE)