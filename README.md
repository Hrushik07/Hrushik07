import { motion } from 'framer-motion';
import { FaGithub, FaLinkedin } from 'react-icons/fa';

export default function AboutMe() {
  return (
    <div className="p-6 max-w-2xl mx-auto space-y-4 text-gray-800">
      <motion.div
        initial={{ opacity: 0, y: 20 }}
        animate={{ opacity: 1, y: 0 }}
        transition={{ duration: 0.8 }}
        className="text-2xl font-bold text-indigo-600"
      >
        👋 Hi there, I’m Hrushik S (@Hrushik07)
      </motion.div>
      <motion.p
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ delay: 0.3, duration: 0.8 }}
        className="text-lg"
      >
        👀 I’m passionate about building web applications and learning new technologies.
      </motion.p>
      <motion.p
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ delay: 0.5, duration: 0.8 }}
      >
        🌱 Currently learning <strong>Next.js</strong> and <strong>TypeScript</strong> to level up my frontend skills.
      </motion.p>
      <motion.p
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ delay: 0.7, duration: 0.8 }}
      >
        💻 Skilled in <strong>HTML</strong>, <strong>CSS</strong>, <strong>JavaScript</strong>, <strong>React.js</strong>, <strong>Redux Toolkit</strong>, <strong>Tailwind CSS</strong>, <strong>Material UI</strong>, and <strong>Axios</strong>.
      </motion.p>
      <motion.p
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ delay: 0.9, duration: 0.8 }}
      >
        🧩 I enjoy turning complex problems into simple, beautiful, and intuitive UIs.
      </motion.p>
      <motion.p
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ delay: 1.1, duration: 0.8 }}
      >
        💞️ Open to collaborating on beginner-friendly open-source projects and frontend apps.
      </motion.p>
      <motion.div
        className="flex items-center space-x-4"
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ delay: 1.3, duration: 0.8 }}
      >
        📫 Reach me:
        <a href="https://linkedin.com/in/hrushik-hrush-189040247" target="_blank" rel="noopener noreferrer" className="text-blue-600 hover:underline flex items-center gap-1">
          <FaLinkedin /> LinkedIn
        </a>
        <span>|</span>
        <a href="mailto:hrushik.017@gmail.com" className="text-red-600 hover:underline">hrushik.017@gmail.com</a>
      </motion.div>
      <motion.p
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ delay: 1.5, duration: 0.8 }}
      >
        😄 Pronouns: <strong>He/Him</strong>
      </motion.p>
      <motion.p
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ delay: 1.7, duration: 0.8 }}
      >
        ⚡ Fun fact: I love solving UI bugs more than solving puzzles 😄
      </motion.p>
    </div>
  );
}
