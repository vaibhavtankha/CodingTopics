void backtrack(List<Integer> state, int start, int[] input, List<List<Integer>> result) {
    // ✅ Base case – can be customized based on the problem
    if (isGoalState(state)) {
        result.add(new ArrayList<>(state));
        return;
    }

    for (int i = start; i < input.length; i++) {
        // ✅ Optional: Skip duplicates to avoid repeated subsets
        if (i > start && input[i] == input[i - 1]) continue;

        // ✅ Choose
        state.add(input[i]);

        // ✅ Explore – use 'i + 1' to avoid reuse, 'i' if repetition is allowed
        backtrack(state, i + 1, input, result);

        // ✅ Un-choose (Backtrack)
        state.remove(state.size() - 1);
    }
}
