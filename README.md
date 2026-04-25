# 🎵 Music Genre Networks & Consumer Behavior Analysis

Understanding how music preferences evolve is key to successful artist positioning — this project uses network analytics to uncover hidden relationships between genres and the role of social influence in shaping listener behavior.

---

## 🚨 The Problem

Music platforms operate in highly fragmented markets where understanding how genres relate and how user preferences spread is complex. Traditional analysis fails to capture the interconnected nature of music consumption and the influence of social relationships.

This results in:
- unclear genre positioning strategies  
- inefficient targeting of audiences  
- missed opportunities for cross-genre promotion  

---

## 💡 The Solution

This project applies network analysis to map relationships between music genres and understand how user preferences are structured. By modeling user–genre interactions and projecting them into a genre similarity network, the analysis reveals how different genres connect and influence each other.

It further explores how social connections shape music preferences, providing a deeper understanding of how tastes spread across networks.

---

## 📊 Business Impact

The insights enable more effective and data-driven music strategy decisions.

This supports:
- smarter artist and album positioning  
- targeted marketing within genre clusters  
- leveraging social influence for organic growth  
- improved recommendation and discovery systems  

---

## 🛠️ How it was done

The analysis was conducted using the Deezer dataset, constructing a bipartite network linking users to their preferred genres. This was projected into a genre-to-genre network to measure similarity based on shared listeners.

Results showed that “Pop” acts as a central connector across genres, with strong links to Dance and Rock, indicating dominant cross-genre listening patterns (page 3).

Community detection using the Louvain algorithm revealed four major genre clusters with high internal connectivity but low modularity, suggesting fluid boundaries between genres rather than rigid segments (page 3–4).

Further analysis compared social and non-social networks, showing that users connected socially share significantly more similar music preferences, with higher clustering and connectivity, indicating strong social influence on consumption patterns (page 4).

---

## 📄 Full Case Study

👉 [View Report](./Report.pdf)
