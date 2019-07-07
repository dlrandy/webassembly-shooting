webassembly文件以module开头
(module
  (export 'sqrt' (func $sqrt))
  func $sqrt(
    (param f32 xx)
    (result f32)
    (
      f32.sqrt(get_local xx )
    )
  )
)

https://mbebenita.github.io/WasmExplorer/
https://webassembly.studio/








