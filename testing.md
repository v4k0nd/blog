
| pages | [main](README.md) | [testing linking](testing\ linking.md) |
| ---- | ---- | ---- |

Page for testing how things work 🔧 with ObsidianMD and traditional Markdown / Github-flavoured Markdown
## linking: 
- [[testing linking]] <- as i guessed this notation is obsidian specific
- [Testing linkingg](Testing linking.md) <- correct linkage \[\<text\>\]\(\<source\>\)

## images:
Original image, normal Md style:
![alt text](github-octocat.webp)
ObsidianMD style, with image resize:
![[github-octocat.webp\|85]]<- using ObsidianMD, of course it wont work

Normal Md style, with image resize:
![\|85](github-octocat.webp) <-kinda weird that you need to set the size in the bracket \[ \|\<size\>\]\(\<link\>\)
