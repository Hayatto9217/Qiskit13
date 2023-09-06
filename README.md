# Qiskit13

#参照サイト
https://qiskit.org/documentation/locale/ja_JP/tutorials/simulators/5_noise_transformation.html

#注意
このノートブックは、量子ノイズチャネルを、他のより適切なノイズチャネルに変換するために Qiskit Aer ユーティリティ関数 approximate_quantum_error と approximate_noise_model を使用する方法を示します。

私たちのガイド例はCliffordシミュレーションです。 Cliffordシミュレーターは、制限された非普遍的なゲート (Cliffordゲート) からのみゲートを含む量子計算を効率的にシミュレートすることができます。 すべての量子ノイズをシミュレーションに追加できるわけではありません。 そこで、Cliffordシミュレーターでシミュレーションできる「近い」ノイズチャネルを見つけることを目指しています。
