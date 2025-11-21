{
  id: "unique-id-string",
  gradeBand: "K-2" | "3-5" | "6-8" | "Alg1" | "Geo" | "Alg2" | "PreCalc",
  track: "operations" | "reasoning",
  difficulty: "easy" | "medium" | "hard",
  errorType: "short-label-for-error-pattern",
  inattention: true | false,

  prompt: "Short description of the situation / question.",
  work: "What the 'student' wrote or did (their work).",

  options: [
    "Choice A text...",
    "Choice B text...",
    "Choice C text...",
    "Choice D text..."
  ],
  correctIndex: 0, // 0-based index into the options array
  hint: "Gentle hint that points toward the key idea.",
  insight: "Teacher-style explanation of what went wrong and how to fix it."
}
