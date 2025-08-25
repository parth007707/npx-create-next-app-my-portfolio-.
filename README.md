export default function Home() {
  return (
    <div className="min-h-screen bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 flex items-center justify-center p-6">
      <div className="bg-white rounded-2xl shadow-2xl max-w-2xl w-full p-10 text-center">
        <h1 className="text-4xl font-bold text-gray-900 mb-4">
          Hi, I'm Parth Atrishi 👋
        </h1>
        <p className="text-lg text-gray-700 mb-6">
          I am a <span className="font-semibold">B.Tech Biotechnology</span> student at
          I.M.S Engineering College (2023–2027) with a keen interest in
          <span className="font-semibold"> Python Development</span> and modern web technologies like React & Next.js.
        </p>

        <div className="grid grid-cols-1 sm:grid-cols-2 gap-4 mb-6">
          <a
            href="https://github.com/parth007707"
            target="_blank"
            rel="noopener noreferrer"
            className="bg-indigo-600 hover:bg-indigo-700 text-white font-medium py-3 px-5 rounded-xl shadow-md transition"
          >
            GitHub Profile
          </a>
          <a
            href="mailto:atrishiparth05@gmail.com"
            className="bg-pink-600 hover:bg-pink-700 text-white font-medium py-3 px-5 rounded-xl shadow-md transition"
          >
            Contact Me
          </a>
        </div>

        <div className="text-gray-600">
          <p className="mb-1">📞 7464849860</p>
          <p>📧 atrishiparth05@gmail.com</p>
        </div>
      </div>
    </div>
  );
}
