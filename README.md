# 🎯 Pathfinder Visualizer

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://pathfinder-visualizer-teal.vercel.app/)


An interactive web-based pathfinding visualization tool that brings popular algorithms to life! Watch A* and Dijkstra's algorithms find the shortest path through custom mazes with beautiful real-time animations.

![Pathfinder Demo](https://pathfinder-visualizer-teal.vercel.app/)

## ✨ Features

- 🚀 **A* Algorithm**: Efficient pathfinding with heuristic optimization
- 📈 **Dijkstra's Algorithm**: Classic shortest path algorithm
- 🎨 **Real-time Visualization**: Watch algorithms explore nodes step by step
- 🖱️ **Interactive Maze Builder**: Click to create custom obstacles
- 📱 **Responsive Design**: Works perfectly on desktop and mobile
- 🎮 **Intuitive Controls**: Easy-to-use interface with clear instructions
- 🧹 **Reset Functionality**: Clear grid and start fresh anytime

## 🎮 How to Play

1. **Set Start Point**: Click anywhere on the grid to place your orange start point
2. **Set End Point**: Click again to place your purple destination
3. **Draw Obstacles**: Left-click to create black barriers for more challenge
4. **Choose Algorithm**: Click "Run A*" or "Run Dijkstra's" to watch the magic happen
5. **Observe**: Watch as the algorithm explores (red), finds the path (blue), and marks visited nodes
6. **Reset**: Use "Clear Grid" to start over with a new maze

## 🎨 Color Legend

| Color | Meaning |
|-------|---------|
| 🟠 Orange | Start Point |
| 🟣 Purple | End Point |
| ⬜ White | Empty Space |
| ⬛ Black | Obstacle/Wall |
| 🟢 Green | Open Set (to be explored) |
| 🔴 Red/Orange | Closed Set (already explored) |
| 🔵 Blue | Final Shortest Path |

## 🚀 Live Demo

Check out the live demo: [Pathfinder Visualizer](https://pathfinder-visualizer-teal.vercel.app/)

## 🛠️ Technologies Used

- **HTML5 Canvas**: For smooth graphics rendering
- **Vanilla JavaScript**: ES6+ features for clean, efficient code
- **CSS3**: Modern styling with gradients and animations
- **Responsive Design**: Mobile-first approach

## 📁 Project Structure

```
pathfinder-visualizer/
├── index.html          # Main application file
├── README.md          # You're reading it!
├── LICENSE            # MIT License
└── assets/           # Screenshots and demo images
    └── demo.gif
```

## 🔧 Local Development

1. **Clone the repository**
   ```bash
   git clone git@github.com:Abhiz2411/pathfinder-visualizer.git
   cd pathfinder-visualizer
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your preferred browser
   open index.html
   # or
   python -m http.server 8000  # For local server
   ```

## 🌐 Deployment

### AWS S3 + CloudFront
1. Upload `index.html` to your S3 bucket
2. Enable static website hosting
3. Configure CloudFront for global distribution

### AWS Amplify
1. Connect your GitHub repository
2. Amplify will automatically build and deploy
3. Get your live URL instantly

### Netlify (Alternative)
1. Drag and drop the `index.html` file
2. Get instant deployment with custom domain support

## 🔍 Algorithm Details

### A* Algorithm
- **Time Complexity**: O(b^d) where b is branching factor and d is depth
- **Space Complexity**: O(b^d)
- **Optimal**: Yes (with admissible heuristic)
- **Complete**: Yes
- **Heuristic**: Manhattan Distance

### Dijkstra's Algorithm
- **Time Complexity**: O(V²) or O(E + V log V) with priority queue
- **Space Complexity**: O(V)
- **Optimal**: Yes
- **Complete**: Yes
- **Guarantee**: Always finds shortest path

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

1. **Report Bugs**: Open an issue with details
2. **Feature Requests**: Suggest new algorithms or improvements
3. **Code Contributions**: Fork, create branch, make changes, submit PR

### Development Guidelines
- Follow existing code style
- Test on multiple browsers
- Ensure mobile responsiveness
- Update README if needed

## 🎯 Future Enhancements

- [ ] **More Algorithms**: BFS, DFS, Greedy Best-First Search
- [ ] **Maze Generation**: Random maze generation algorithms
- [ ] **Speed Control**: Adjustable animation speed
- [ ] **Path Statistics**: Show path length and nodes explored
- [ ] **Save/Load Mazes**: Export and import custom mazes
- [ ] **Diagonal Movement**: Allow 8-directional pathfinding
- [ ] **Weighted Nodes**: Different terrain costs

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Abhijit Zende**
- GitHub: [@Abhiz2411](https://github.com/Abhiz2411/pathfinder-visualizer)
- LinkedIn: [zende-abhijit](https://www.linkedin.com/in/zende-abhijit/)
- Portfolio: [abhijitzende.com](https://www.abhijitzende.com/)

## 🙏 Acknowledgments

- Inspired by classic pathfinding algorithm demonstrations
- Built with modern web technologies for optimal performance
- Thanks to the computer science community for algorithm research

## ⭐ Show Your Support

If this project helped you learn about pathfinding algorithms, please give it a star! ⭐

---

<div align="center">
  <p>Made with ❤️ by Abhijit Zende</p>
  <p>
    <a href="#top">Back to Top ⬆️</a>
  </p>
</div>