<div class="bg-orange-600 min-h-screen flex flex-col items-center justify-center p-4">
    <div class="w-full max-w-sm">
        <div class="mb-8 text-center">
            <img src="https://placehold.co/100x100" alt="Logo" class="mx-auto mb-4">
            <h2 class="text-3xl font-bold text-white">Login</h2>
        </div>
        <form class="space-y-6">
            <div class="bg-zinc-800 rounded-lg p-4">
                <label class="block mb-2 text-sm font-medium text-zinc-300">Username</label>
                <input type="text" name="username" class="w-full p-2 rounded bg-zinc-700 text-white placeholder-zinc-400" placeholder="newnuman">
            </div>
            <div class="bg-zinc-800 rounded-lg p-4">
                <label class="block mb-2 text-sm font-medium text-zinc-300">Password</label>
                <input type="password" name="password" class="w-full p-2 rounded bg-zinc-700 text-white placeholder-zinc-400" placeholder="********">
            </div>
            <div class="flex items-center justify-between">
                <label class="flex items-center text-sm text-zinc-300">
                    <input type="checkbox" class="form-checkbox h-4 w-4 text-orange-500 rounded">
                    <span class="ml-2">Remember</span>
                </label>
                <a href="#" class="text-sm text-red-400 hover:text-red-300">Forgot password?</a>
            </div>
            <button type="submit" class="w-full py-3 mt-6 bg-orange-500 rounded-lg text-white font-bold hover:bg-orange-400">Login</button>
            <p class="mt-8 text-center text-white">
                No account yet? <a href="#" class="text-red-400 hover:text-red-300">Sign Up</a>
            </p>
        </form>
    </div>
</div>
