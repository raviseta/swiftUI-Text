# SwiftUI
Simple SwiftUI project to demostrate Text properties.

## Code

```
struct ContentView: View {
    var body: some View {
        Text("Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard.")
            .foregroundColor(.red)
            .background(.yellow)
            .fontWeight(.bold)
            .font(.system(size: 35))
            .multilineTextAlignment(.center)
            .lineLimit(3)
            .truncationMode(.head)
            .lineSpacing(15)
            .padding()
    }
}
```

### Output
![Screenshot 2023-02-02 at 1 46 19 PM](https://user-images.githubusercontent.com/18464085/216274997-ec917c71-3be7-4b9c-9c7c-f335913ee774.png)
